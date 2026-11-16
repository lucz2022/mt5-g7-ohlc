# MT5 外汇 OHLC 数据使用说明

本仓库每 15 分钟发布一次 IC Markets MT5 行情。覆盖 AUD、CAD、CHF、EUR、GBP、JPY 和 USD 的 21 种两两组合，包含 5 个周期的已收盘 K 线、Bid/Ask 报价快照和价格结构报告。

## 文件入口

| 文件 | 内容 |
| --- | --- |
| [价格结构报告](ohlc/price_structure.md) | 21 个货币对的 24 小时高低区间、最近已收盘日线和周线的高低点、EMA20/50/200、ATR14、确认摆动和收盘破位。 |
| [最近 24 小时 K 线](ohlc/last_24h.json) | 按货币对和周期列出窗口内的已收盘 K 线，可直接供程序读取。 |
| [数据清单](ohlc/manifest.json) | 105 个货币对与周期组合的路径、状态、首末时间、样本数和 SHA-256，也索引快照和报告。 |
| [报价快照](ohlc/quotes.json) | 21 个货币对的采集时点、最近 tick 时间、Bid、Ask 和以 point 为单位的点差。 |
| [历史文件示例](ohlc/pairs/EURUSD/M15.json) | 每个货币对和周期独立存放，路径为 `ohlc/pairs/{SYMBOL}/{TIMEFRAME}.json`。 |

## 24 小时口径

所有行情时间使用 UTC，字段以 `Z` 结尾。每轮采集把最近一个 M15 收盘边界作为统一截止时间，再向前推 24 个自然小时。K 线的 `close_time_utc` 满足 `window_start_utc < close_time_utc <= window_end_utc` 才纳入快照。H1、H4、D1 和 W1 沿用券商原生 K 线边界。

周末和休市仍计入自然小时。某周期在窗口内没有收盘时，`bars_count` 为 `0`，`bars` 为 `[]`。结合 `source_status`、`source_reason` 与清单判断这一结果。例如周初的 24 小时窗口可以有 M15 和 H1 数据，同时没有新的周线收盘。

历史文件采用滚动窗口，M15、H1 各最多 1,000 根，H4、D1 各最多 500 根，W1 最多 300 根。价格结构报告用这些历史文件计算指标，指标行要求至少 250 根连续有效的已收盘 K 线。具体算法见报告的「计算口径」。

## 读取和检查

1. 从仓库提交历史选定一个 commit SHA，用该 SHA 读取 `ohlc/manifest.json` 和它引用的文件，避免跨版本混读。
2. 读取单个周期时，在清单的 `datasets` 中按 `symbol` 和 `timeframe` 查找记录。检查 `status`、`reason`、`path`、`last_closed_bar_utc` 和 `sha256`。读取整个 24 小时窗口时，使用清单的 `last_24h_path` 和 `last_24h_sha256`。
3. 对下载的原始文件字节计算 SHA-256。新鲜度以最后一根 K 线的收盘时间或报价的 tick 时间为准，并结合券商交易时段判断。

| 历史状态 | 含义 |
| --- | --- |
| `OK` | 已通过采集和历史样本检查。最新时点见 `last_closed_bar_utc`。 |
| `INSUFFICIENT_HISTORY` | 有实际 K 线，可用的连续样本不足。 |
| `STALE` | 历史滞后，或本轮取数失败后保留了旧文件。 |
| `INVALID` | 本轮校验发现异常，原因见 `reason`。 |
| `UNAVAILABLE` | 暂无可读历史文件，`path` 为 `null`。 |

## 运行方式

Windows 计划任务名为 `MT5-G7-OHLC-Publish`，每 15 分钟在 MT5 的交互会话中运行一次。采集依赖该用户保持登录且 MT5 连接行情服务器。周期文件按内容变化更新，清单、快照、报价和报告在同一提交发布。运行记录写入部署目录的 `publisher.log`，其中可核对 `push_status`、`commit` 和数据集状态计数。
