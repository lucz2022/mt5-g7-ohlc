# EURAUD candidate evidence

JSON SHA-256: 905212522f23a4312671c07632f69a9649380ddec314a4a31f8ec8c30de6dfd7

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "EURAUD",
  "as_of_utc": "2026-11-16T17:45:00Z",
  "price_basis": "BID",
  "status": "REJECT",
  "reasons": [
    "D1_H4_TREND_CONFLICT"
  ],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/EURAUD/D1.json",
      "sha256": "c1b5ed5ff55d79b2aa02f3b20ecf8b2273111806c4b74e9d5a7cd72cc4004193",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURAUD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T02:47:21Z",
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
      "path": "ohlc/pairs/EURAUD/H4.json",
      "sha256": "d30e34a4df8e9de518241504a0c136c103364002db34f725431a4ef78358cefb",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURAUD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T14:01:12Z",
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
      "path": "ohlc/pairs/EURAUD/H1.json",
      "sha256": "6dd9a93b36140d043e52427797b5ac45555ce341eded95b57a8ce0e0e17381cd",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURAUD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T17:01:11Z",
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
      "path": "ohlc/pairs/EURAUD/M15.json",
      "sha256": "7885649b5476de547ee70d1f1002bbbd472d37faed57bc534a71deaef6acde0d",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURAUD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T17:46:09Z",
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
      "path": "ohlc/pairs/EURAUD/W1.json",
      "sha256": "7d91527f95246550d91ae825fd66280c7d162f909679c80b84969f0cfbdfb4dd",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURAUD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T02:47:54Z",
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
      "close": 1.6266699999999998,
      "ema": {
        "20": 1.611624532922305,
        "50": 1.6126773996861135,
        "200": 1.641695958600369
      },
      "ema20_change_5bars": 0.007675821076567724,
      "atr14": 0.01098485411010881,
      "trend": "NEUTRAL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-16T14:00:00Z",
      "close": 1.6312600000000002,
      "ema": {
        "20": 1.6262021150713466,
        "50": 1.6199204148699649,
        "200": 1.6116288163885744
      },
      "ema20_change_5bars": 0.0025103314128571697,
      "atr14": 0.0039149304707519015,
      "trend": "BUY"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T17:00:00Z",
      "close": 1.63066,
      "ema": {
        "20": 1.6297271741407986,
        "50": 1.6277453166511044,
        "200": 1.6200152034877855
      },
      "ema20_change_5bars": 0.0007486359338810811,
      "atr14": 0.001985585184725052,
      "trend": "BUY"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T17:45:00Z",
      "close": 1.63104,
      "ema": {
        "20": 1.6309110239752407,
        "50": 1.6303789775150601,
        "200": 1.6278077918870544
      },
      "ema20_change_5bars": 1.2130494687401239e-05,
      "atr14": 0.0008763213680209117,
      "trend": "BUY"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-14T22:00:00Z",
      "close": 1.6266699999999998,
      "ema": {
        "20": 1.6214024418192734,
        "50": 1.6503709652694725,
        "200": 1.6523590961035424
      },
      "ema20_change_5bars": -0.007352814354464776,
      "atr14": 0.020906676969539625,
      "trend": "SELL"
    }
  },
  "candidates": [],
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
    "broker_symbol": "EURAUD",
    "tick_time_utc": "2026-11-16T17:46:06Z",
    "bid": 1.6311200000000001,
    "ask": 1.6312600000000002,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 14.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -3e-12
  },
  "rtv": {
    "value": 0.819672131147541,
    "baseline_median": 1098.0,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-16T17:45:00Z"
  }
}
```
