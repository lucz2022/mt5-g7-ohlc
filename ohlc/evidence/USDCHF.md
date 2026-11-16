# USDCHF candidate evidence

JSON SHA-256: 034a07815bcf7a341fcec278c53618ad89adc5676b4cf217989f36ede79411f9

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "USDCHF",
  "as_of_utc": "2026-11-16T21:00:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/USDCHF/D1.json",
      "sha256": "c9af53559c07e3189a926a9c93c074b72d8d23136a5b95ac89f1065343b66ff8",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T02:38:22Z",
      "bar_alignment": {
        "time_source": "MT5_UNIX_UTC",
        "source_encoding": "IC_MARKETS_SERVER_WALL_TIME",
        "broker_timezone": null,
        "broker_utc_offset_minutes_at_collection": 120,
        "daily_rollover_server_time": "00:00:00",
        "h4_anchor_server_hours": [
          0,
          4,
          8,
          12,
          16,
          20
        ],
        "week_start_server_day": "SUNDAY",
        "dst_handling": "EXPLICIT_OFFSET_HISTORY",
        "dst_reference_timezone": "America/New_York",
        "source_evidence": "https://cdn.icmarkets.com/uploads/FSA/Forex-Product-Specificiation-Sheet.pdf"
      }
    },
    "H4": {
      "path": "ohlc/pairs/USDCHF/H4.json",
      "sha256": "2bfd73203822dc31899ad26f4909321059a41a21c9f97a88a3fa6028451182b6",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T18:01:08Z",
      "bar_alignment": {
        "time_source": "MT5_UNIX_UTC",
        "source_encoding": "IC_MARKETS_SERVER_WALL_TIME",
        "broker_timezone": null,
        "broker_utc_offset_minutes_at_collection": 120,
        "daily_rollover_server_time": "00:00:00",
        "h4_anchor_server_hours": [
          0,
          4,
          8,
          12,
          16,
          20
        ],
        "week_start_server_day": "SUNDAY",
        "dst_handling": "EXPLICIT_OFFSET_HISTORY",
        "dst_reference_timezone": "America/New_York",
        "source_evidence": "https://cdn.icmarkets.com/uploads/FSA/Forex-Product-Specificiation-Sheet.pdf"
      }
    },
    "H1": {
      "path": "ohlc/pairs/USDCHF/H1.json",
      "sha256": "e064885f1297538f2d0e2a46b856010ded15cebc0e1c621956e7815f9561e6f4",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T21:01:08Z",
      "bar_alignment": {
        "time_source": "MT5_UNIX_UTC",
        "source_encoding": "IC_MARKETS_SERVER_WALL_TIME",
        "broker_timezone": null,
        "broker_utc_offset_minutes_at_collection": 120,
        "daily_rollover_server_time": "00:00:00",
        "h4_anchor_server_hours": [
          0,
          4,
          8,
          12,
          16,
          20
        ],
        "week_start_server_day": "SUNDAY",
        "dst_handling": "EXPLICIT_OFFSET_HISTORY",
        "dst_reference_timezone": "America/New_York",
        "source_evidence": "https://cdn.icmarkets.com/uploads/FSA/Forex-Product-Specificiation-Sheet.pdf"
      }
    },
    "M15": {
      "path": "ohlc/pairs/USDCHF/M15.json",
      "sha256": "e9d8d1f1a15ef2b57959598f5c6268140acea4c6943014152d88c9b7a4b28faf",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T21:01:08Z",
      "bar_alignment": {
        "time_source": "MT5_UNIX_UTC",
        "source_encoding": "IC_MARKETS_SERVER_WALL_TIME",
        "broker_timezone": null,
        "broker_utc_offset_minutes_at_collection": 120,
        "daily_rollover_server_time": "00:00:00",
        "h4_anchor_server_hours": [
          0,
          4,
          8,
          12,
          16,
          20
        ],
        "week_start_server_day": "SUNDAY",
        "dst_handling": "EXPLICIT_OFFSET_HISTORY",
        "dst_reference_timezone": "America/New_York",
        "source_evidence": "https://cdn.icmarkets.com/uploads/FSA/Forex-Product-Specificiation-Sheet.pdf"
      }
    },
    "W1": {
      "path": "ohlc/pairs/USDCHF/W1.json",
      "sha256": "1c53bb4427b1804806675a995580b07039d5f6814eb08b314f7b05c654bcec12",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T02:33:06Z",
      "bar_alignment": {
        "time_source": "MT5_UNIX_UTC",
        "source_encoding": "IC_MARKETS_SERVER_WALL_TIME",
        "broker_timezone": null,
        "broker_utc_offset_minutes_at_collection": 120,
        "daily_rollover_server_time": "00:00:00",
        "h4_anchor_server_hours": [
          0,
          4,
          8,
          12,
          16,
          20
        ],
        "week_start_server_day": "SUNDAY",
        "dst_handling": "EXPLICIT_OFFSET_HISTORY",
        "dst_reference_timezone": "America/New_York",
        "source_evidence": "https://cdn.icmarkets.com/uploads/FSA/Forex-Product-Specificiation-Sheet.pdf"
      }
    }
  },
  "metrics": {
    "D1": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-13T22:00:00Z",
      "close": 0.83881,
      "ema": {
        "20": 0.8265650501285572,
        "50": 0.8234880511700068,
        "200": 0.8113353605167671
      },
      "ema20_change_5bars": 0.003098551198146726,
      "atr14": 0.0060289963953888154,
      "trend": "BUY"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-16T18:00:00Z",
      "close": 0.83944,
      "ema": {
        "20": 0.8354138628163461,
        "50": 0.8297888221128635,
        "200": 0.8256154174968104
      },
      "ema20_change_5bars": 0.002584167023850892,
      "atr14": 0.002171937178119736,
      "trend": "BUY"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T21:00:00Z",
      "close": 0.84026,
      "ema": {
        "20": 0.8394477500698675,
        "50": 0.8377143008233765,
        "200": 0.8299135138689757
      },
      "ema20_change_5bars": 0.0003025489336866416,
      "atr14": 0.0010445342670435066,
      "trend": "BUY"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T21:00:00Z",
      "close": 0.84026,
      "ema": {
        "20": 0.8397572274234685,
        "50": 0.8395716812644695,
        "200": 0.8376504255259453
      },
      "ema20_change_5bars": 0.00019248724247600268,
      "atr14": 0.00044925249442790256,
      "trend": "BUY"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-14T22:00:00Z",
      "close": 0.83881,
      "ema": {
        "20": 0.8177293760771989,
        "50": 0.8104723925673032,
        "200": 0.8493852612108518
      },
      "ema20_change_5bars": 0.00614406048752969,
      "atr14": 0.012704237441014843,
      "trend": "BUY"
    }
  },
  "candidates": [
    {
      "symbol": "USDCHF",
      "enabled": 0,
      "direction": "BUY",
      "mode": "PULLBACK",
      "zone_low": 0.83848,
      "zone_high": 0.8388,
      "invalidation": 0.83822,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.75,
      "factor_group": "USD_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 1.3978,
      "pivot": {
        "side": "LOW",
        "level": 0.83864,
        "index": 991,
        "confirmed_index": 993,
        "pivot_utc": "2026-11-16T13:00:00Z",
        "confirmed_utc": "2026-11-16T15:00:00Z"
      },
      "breakout_close_utc": null,
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": true,
      "valid_until_utc": "2026-11-17T21:00:00Z"
    }
  ],
  "enabled": 0,
  "backtested": false,
  "execution_checks": "PENDING_EA_LIVE_CHECKS",
  "parameters": {
    "zone_half_atr": 0.15,
    "stop_buffer_atr": 0.25,
    "max_distance_atr": 3,
    "pivot_lookback_h1": 120,
    "trend_rule": "close vs EMA50 + EMA20 vs EMA50 + EMA20 slope5",
    "rr_defaults": [
      1.2,
      2.5
    ]
  },
  "quote": {
    "broker_symbol": "USDCHF",
    "tick_time_utc": "2026-11-16T21:01:07Z",
    "bid": 0.84022,
    "ask": 0.84031,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 9.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -3e-12
  },
  "rtv": {
    "value": 0.49105367793240556,
    "baseline_median": 503.0,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-16T21:00:00Z"
  }
}
```
