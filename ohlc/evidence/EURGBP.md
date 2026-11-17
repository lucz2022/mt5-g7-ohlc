# EURGBP candidate evidence

JSON SHA-256: 4afc9a4e448c4ef4f2b44a148361ec3c2bcaeba100c863aae6917908b4809bbd

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "EURGBP",
  "as_of_utc": "2026-11-17T00:30:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/EURGBP/D1.json",
      "sha256": "51e71e24ce6f0919265eb7a9ab101031797ecf9dd4b202ccd903e93e74ac5440",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURGBP",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T22:01:20Z",
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
      "path": "ohlc/pairs/EURGBP/H4.json",
      "sha256": "12588b778cef18ac2b031cb21a344fb7d8f1db25eb858ffc0901cdec9d722863",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURGBP",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T22:01:20Z",
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
      "path": "ohlc/pairs/EURGBP/H1.json",
      "sha256": "2cd3f49d92940015c64464ed5be16daea94f9cb858ff52a3cdce604f70ed7faf",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURGBP",
      "digits": 5,
      "retrieved_at_utc": "2026-11-17T00:01:10Z",
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
      "path": "ohlc/pairs/EURGBP/M15.json",
      "sha256": "26f50987ff4007d9370174585b20dc6d6f296b11bab24141f8f1699b206b367f",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURGBP",
      "digits": 5,
      "retrieved_at_utc": "2026-11-17T00:31:10Z",
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
      "path": "ohlc/pairs/EURGBP/W1.json",
      "sha256": "bd8f5e47bbf517889fea6cf72091c16cc5e596b48d66b8817e377e75de8cbe6f",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURGBP",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T02:33:48Z",
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
      "last_closed_bar_utc": "2026-11-16T22:00:00Z",
      "close": 0.83402,
      "ema": {
        "20": 0.8369351115590115,
        "50": 0.8432579558118272,
        "200": 0.8548281245021767
      },
      "ema20_change_5bars": -0.001297815401207103,
      "atr14": 0.0026594946406826793,
      "trend": "SELL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-16T22:00:00Z",
      "close": 0.83402,
      "ema": {
        "20": 0.8348647204885687,
        "50": 0.8351523441242074,
        "200": 0.8403465217590884
      },
      "ema20_change_5bars": -0.000356267812821498,
      "atr14": 0.0009681243053471624,
      "trend": "SELL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-17T00:00:00Z",
      "close": 0.83416,
      "ema": {
        "20": 0.8342943557711785,
        "50": 0.8346322330306144,
        "200": 0.8351235508036678
      },
      "ema20_change_5bars": -0.00015684375655700133,
      "atr14": 0.0005184077866634835,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-17T00:30:00Z",
      "close": 0.83416,
      "ema": {
        "20": 0.834081355651562,
        "50": 0.8341952319956151,
        "200": 0.834617310521731
      },
      "ema20_change_5bars": 5.7420090867621454e-05,
      "atr14": 0.00026793509477040763,
      "trend": "NEUTRAL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-14T22:00:00Z",
      "close": 0.83419,
      "ema": {
        "20": 0.8488136204488735,
        "50": 0.8560653547764873,
        "200": 0.857728320852909
      },
      "ema20_change_5bars": -0.008318838006489138,
      "atr14": 0.006028882486615227,
      "trend": "SELL"
    }
  },
  "candidates": [
    {
      "symbol": "EURGBP",
      "enabled": 0,
      "direction": "SELL",
      "mode": "PULLBACK",
      "zone_low": 0.83447,
      "zone_high": 0.83463,
      "invalidation": 0.83476,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.5,
      "factor_group": "GBP_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 0.598,
      "pivot": {
        "side": "HIGH",
        "level": 0.83455,
        "index": 996,
        "confirmed_index": 998,
        "pivot_utc": "2026-11-16T21:00:00Z",
        "confirmed_utc": "2026-11-16T23:00:00Z"
      },
      "breakout_close_utc": null,
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": false,
      "valid_until_utc": "2026-11-18T00:30:00Z"
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
    "broker_symbol": "EURGBP",
    "tick_time_utc": "2026-11-17T00:31:07Z",
    "bid": 0.83413,
    "ask": 0.83423,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 10.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": 1e-12
  },
  "rtv": {
    "value": 2.3485477178423237,
    "baseline_median": 241.0,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-17T00:30:00Z"
  }
}
```
