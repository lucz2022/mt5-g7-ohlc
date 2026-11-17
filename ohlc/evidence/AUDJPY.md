# AUDJPY candidate evidence

JSON SHA-256: b6ab5bc2c4db453d33744760d02a182c063f9b2cd1b75feabbeb11c9c64f4ad0

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "AUDJPY",
  "as_of_utc": "2026-11-17T01:15:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/AUDJPY/D1.json",
      "sha256": "032fc8b28a287226547ddb82eb027caacd627bbf9ea06ea9eb877dcb8abab21b",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T22:01:21Z",
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
      "path": "ohlc/pairs/AUDJPY/H4.json",
      "sha256": "1806b54b38eed49d9e4fb880766a56967a1ae371b7f46315beb55d3ffbfdc496",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T22:01:21Z",
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
      "path": "ohlc/pairs/AUDJPY/H1.json",
      "sha256": "34a0575897144acd22eff58f471c757317ec11ee74e80831f963ce6d69f5e1c5",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-17T01:01:10Z",
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
      "path": "ohlc/pairs/AUDJPY/M15.json",
      "sha256": "6a22bb83daaf679543a3e4d1b9f2b8c313d3f38cd2f244b21a0b371516a1b24a",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-17T01:16:12Z",
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
      "path": "ohlc/pairs/AUDJPY/W1.json",
      "sha256": "ed60b50730b4bca10923c9088f75bf6d54535be59d38cef0c7e7d7724a76f8ea",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T02:33:50Z",
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
      "close": 107.411,
      "ema": {
        "20": 109.5458614151991,
        "50": 110.38721301940728,
        "200": 110.07791878680607
      },
      "ema20_change_5bars": -0.7051733728590648,
      "atr14": 0.9669497000725891,
      "trend": "SELL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-16T22:00:00Z",
      "close": 107.411,
      "ema": {
        "20": 108.33846678530524,
        "50": 108.99162206382434,
        "200": 110.05687007294574
      },
      "ema20_change_5bars": -0.4589918285595189,
      "atr14": 0.36038450043549947,
      "trend": "SELL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-17T01:00:00Z",
      "close": 107.39,
      "ema": {
        "20": 107.6447563934048,
        "50": 108.03779038761964,
        "200": 108.96778214503898
      },
      "ema20_change_5bars": -0.15922754304564535,
      "atr14": 0.17793759765151254,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-17T01:15:00Z",
      "close": 107.455,
      "ema": {
        "20": 107.42215329141914,
        "50": 107.52651935967009,
        "200": 108.0359704786795
      },
      "ema20_change_5bars": -0.008755164033658502,
      "atr14": 0.09783572367430572,
      "trend": "SELL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-14T22:00:00Z",
      "close": 108.106,
      "ema": {
        "20": 110.75874224221987,
        "50": 109.18192242632672,
        "200": 100.31143286215332
      },
      "ema20_change_5bars": -0.8643746574648361,
      "atr14": 2.078804028817713,
      "trend": "NEUTRAL"
    }
  },
  "candidates": [
    {
      "symbol": "AUDJPY",
      "enabled": 0,
      "direction": "SELL",
      "mode": "BREAKOUT",
      "zone_low": 107.48,
      "zone_high": 107.534,
      "invalidation": 107.578,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.5,
      "factor_group": "JPY_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 0.1405,
      "pivot": {
        "side": "LOW",
        "level": 107.507,
        "index": 990,
        "confirmed_index": 992,
        "pivot_utc": "2026-11-16T16:00:00Z",
        "confirmed_utc": "2026-11-16T18:00:00Z"
      },
      "breakout_close_utc": "2026-11-16T19:00:00Z",
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": true,
      "valid_until_utc": "2026-11-18T01:15:00Z"
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
    "broker_symbol": "AUDJPY",
    "tick_time_utc": "2026-11-17T01:16:10Z",
    "bid": 107.447,
    "ask": 107.46,
    "digits": 3,
    "point": 0.001,
    "spread_points": 13.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": 9e-12
  },
  "rtv": {
    "value": 2.7421052631578946,
    "baseline_median": 570.0,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-17T01:15:00Z"
  }
}
```
