# EURCHF candidate evidence

JSON SHA-256: 180e2e4a63044b3a4e9848702626b7bf517e306be7157410d8189d12b47259f8

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "EURCHF",
  "as_of_utc": "2026-11-24T16:15:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/EURCHF/D1.json",
      "sha256": "e44e150860a17986bf5790531cf0186dbdf6b861bde546725917e2c18d5d42c6",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T03:31:10Z",
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
      "path": "ohlc/pairs/EURCHF/H4.json",
      "sha256": "c7018589ac3578e2320f5316d7043e18680eacf5a6d80d7f420e29ee9a553f51",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T14:01:12Z",
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
      "path": "ohlc/pairs/EURCHF/H1.json",
      "sha256": "f6bc99ffe3c300fe2c4f70ecfff8f2d774a4a03202b9670448aede6dec4e2115",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T16:01:10Z",
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
      "path": "ohlc/pairs/EURCHF/M15.json",
      "sha256": "79b4174eac0eacfe0ce6ce82bb7bb3a6ddecf4782738d394df25335c8b7dec06",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T16:16:13Z",
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
      "path": "ohlc/pairs/EURCHF/W1.json",
      "sha256": "08610e30ba1ce9e6c33f792d8ed282c797a8552f908ed6b374f8b22fb2fc5ae1",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T03:31:10Z",
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
      "last_closed_bar_utc": "2026-11-23T22:00:00Z",
      "close": 0.91734,
      "ema": {
        "20": 0.9227714642441193,
        "50": 0.9266469456207934,
        "200": 0.9276235102684659
      },
      "ema20_change_5bars": -0.00020806260471506466,
      "atr14": 0.005320065566825296,
      "trend": "SELL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-24T14:00:00Z",
      "close": 0.91825,
      "ema": {
        "20": 0.9208660012401123,
        "50": 0.9219976402233339,
        "200": 0.9247231228569157
      },
      "ema20_change_5bars": -0.0016963334447057665,
      "atr14": 0.0023413304877895973,
      "trend": "SELL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-24T16:00:00Z",
      "close": 0.91651,
      "ema": {
        "20": 0.9183924238458657,
        "50": 0.9197307327989487,
        "200": 0.9219443801922055
      },
      "ema20_change_5bars": -0.00034314945767499605,
      "atr14": 0.0011643012814014457,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-24T16:15:00Z",
      "close": 0.91611,
      "ema": {
        "20": 0.9176041525564003,
        "50": 0.9180753065773274,
        "200": 0.9196884315668122
      },
      "ema20_change_5bars": -0.000676775863564627,
      "atr14": 0.00071346459467467,
      "trend": "SELL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-21T22:00:00Z",
      "close": 0.92136,
      "ema": {
        "20": 0.9273195931591544,
        "50": 0.9273090492819839,
        "200": 0.9547811560766248
      },
      "ema20_change_5bars": -0.004174569610950973,
      "atr14": 0.009882127679685394,
      "trend": "NEUTRAL"
    }
  },
  "candidates": [
    {
      "symbol": "EURCHF",
      "enabled": 0,
      "direction": "SELL",
      "mode": "BREAKOUT",
      "zone_low": 0.91755,
      "zone_high": 0.91789,
      "invalidation": 0.91818,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.5,
      "factor_group": "CHF_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 1.2368,
      "pivot": {
        "side": "LOW",
        "level": 0.91772,
        "index": 990,
        "confirmed_index": 992,
        "pivot_utc": "2026-11-24T07:00:00Z",
        "confirmed_utc": "2026-11-24T09:00:00Z"
      },
      "breakout_close_utc": "2026-11-24T15:00:00Z",
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": true,
      "valid_until_utc": "2026-11-25T16:15:00Z"
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
    "broker_symbol": "EURCHF",
    "tick_time_utc": "2026-11-24T16:16:10Z",
    "bid": 0.91595,
    "ask": 0.91609,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 14.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": 8e-12
  },
  "rtv": {
    "value": 1.1010660980810234,
    "baseline_median": 1172.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-24T16:15:00Z"
  }
}
```
