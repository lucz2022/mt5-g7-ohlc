# USDCAD candidate evidence

JSON SHA-256: 374a0ec5d9608f0f64e7ec42b9cd13ae4ddd91c350b00a14fef50be76af83ae6

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "USDCAD",
  "as_of_utc": "2026-11-24T22:30:00Z",
  "price_basis": "BID",
  "status": "REJECT",
  "reasons": [
    "D1_H4_TREND_CONFLICT"
  ],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/USDCAD/D1.json",
      "sha256": "f46b2ea83a7a593ef27d04acab44cb2d254da3389bac7085f6f0583999f4c463",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T22:01:22Z",
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
      "path": "ohlc/pairs/USDCAD/H4.json",
      "sha256": "8d65e483152072dbdaa0666a2c0393b74edaf37becbf9b83aa99feee57b87ade",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T22:01:22Z",
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
      "path": "ohlc/pairs/USDCAD/H1.json",
      "sha256": "cd52b106710d32f445319381e3fdc192b34076d5b0a28b8edde3ceeb064b6450",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T22:01:22Z",
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
      "path": "ohlc/pairs/USDCAD/M15.json",
      "sha256": "18f545099c46afe88e4aa3e950b6f8b0a657275390a0f6fc57862d956c06276b",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T22:31:08Z",
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
      "path": "ohlc/pairs/USDCAD/W1.json",
      "sha256": "25eef895c68f3c72562a0877a41228efcdd0457fa6cd68119ff4cade1431acca",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T03:31:08Z",
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
      "last_closed_bar_utc": "2026-11-24T22:00:00Z",
      "close": 1.42696,
      "ema": {
        "20": 1.4221909474760268,
        "50": 1.4140619351285406,
        "200": 1.4000958292597958
      },
      "ema20_change_5bars": 0.006824863124073266,
      "atr14": 0.006684103616332658,
      "trend": "BUY"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-24T22:00:00Z",
      "close": 1.42696,
      "ema": {
        "20": 1.4325029615627136,
        "50": 1.4292714844376138,
        "200": 1.4171053784818934
      },
      "ema20_change_5bars": -0.0009439744367110148,
      "atr14": 0.0024857882904697347,
      "trend": "NEUTRAL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-24T22:00:00Z",
      "close": 1.42696,
      "ema": {
        "20": 1.4311132553450432,
        "50": 1.4327712498749308,
        "200": 1.4293395098872188
      },
      "ema20_change_5bars": -0.0025596178268070258,
      "atr14": 0.0013667211933394946,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-24T22:30:00Z",
      "close": 1.42679,
      "ema": {
        "20": 1.42760278747343,
        "50": 1.429693418666367,
        "200": 1.4327556925677987
      },
      "ema20_change_5bars": -0.0004266022573613526,
      "atr14": 0.000575333612299531,
      "trend": "SELL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-21T22:00:00Z",
      "close": 1.43475,
      "ema": {
        "20": 1.4071440658453631,
        "50": 1.3971643673527088,
        "200": 1.3667623728039828
      },
      "ema20_change_5bars": 0.006149316393457838,
      "atr14": 0.014751541097125159,
      "trend": "BUY"
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
    "broker_symbol": "USDCAD",
    "tick_time_utc": "2026-11-24T22:31:05Z",
    "bid": 1.42671,
    "ask": 1.4274200000000001,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 71.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -2.1e-11
  },
  "rtv": {
    "value": 0.04006677796327212,
    "baseline_median": 599.0,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-24T22:30:00Z"
  }
}
```
