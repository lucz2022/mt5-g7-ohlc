# EURJPY candidate evidence

JSON SHA-256: 34a329793234af6d2593a87d8e1094b5c262979376b58e2481aba7d7d07278ff

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "EURJPY",
  "as_of_utc": "2026-11-16T13:00:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/EURJPY/D1.json",
      "sha256": "824568abf858794d66a3eed1d522cdeda70c355d1971002b5cbe563decb88634",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T02:38:23Z",
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
      "path": "ohlc/pairs/EURJPY/H4.json",
      "sha256": "1ef784d0e13ae5067b15da0c4ddb900f9c7e119427291aa9d6f4bf17c5f12ee9",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T10:01:10Z",
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
      "path": "ohlc/pairs/EURJPY/H1.json",
      "sha256": "b182ec16645887efbae54a8e7ba3c8587dab48a590f81d8d09eae95a4fb34965",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T13:01:12Z",
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
      "path": "ohlc/pairs/EURJPY/M15.json",
      "sha256": "15507040402f304ddf331f953f717fe83786abb1a02f84c6a7433be3f151938f",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T13:01:12Z",
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
      "path": "ohlc/pairs/EURJPY/W1.json",
      "sha256": "415348e68e193aa3761625184551a9078097f23a67e52f5ae10d3fc5a4075985",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T02:38:23Z",
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
      "close": 175.994,
      "ema": {
        "20": 176.9363747291276,
        "50": 178.24665870624625,
        "200": 180.63034630009406
      },
      "ema20_change_5bars": -0.0784510591808214,
      "atr14": 1.109949347323922,
      "trend": "SELL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-16T10:00:00Z",
      "close": 175.677,
      "ema": {
        "20": 176.56471280979818,
        "50": 176.79760625274028,
        "200": 177.46932158085698
      },
      "ema20_change_5bars": -0.4109413692994792,
      "atr14": 0.3978725027781574,
      "trend": "SELL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T13:00:00Z",
      "close": 175.645,
      "ema": {
        "20": 175.94285741029088,
        "50": 176.32497090166427,
        "200": 176.77527805218895
      },
      "ema20_change_5bars": -0.1679862361975495,
      "atr14": 0.19416750326165716,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T13:00:00Z",
      "close": 175.645,
      "ema": {
        "20": 175.6843006092704,
        "50": 175.8096587802744,
        "200": 176.32874336365995
      },
      "ema20_change_5bars": -0.049982541210169984,
      "atr14": 0.10264725264929805,
      "trend": "SELL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-14T22:00:00Z",
      "close": 175.994,
      "ema": {
        "20": 179.6515926897719,
        "50": 180.0467548923252,
        "200": 165.9002499106155
      },
      "ema20_change_5bars": -2.1936846363326197,
      "atr14": 2.4762168763191457,
      "trend": "SELL"
    }
  },
  "candidates": [
    {
      "symbol": "EURJPY",
      "enabled": 0,
      "direction": "SELL",
      "mode": "BREAKOUT",
      "zone_low": 175.798,
      "zone_high": 175.856,
      "invalidation": 175.905,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.5,
      "factor_group": "JPY_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 0.788,
      "pivot": {
        "side": "LOW",
        "level": 175.827,
        "index": 985,
        "confirmed_index": 987,
        "pivot_utc": "2026-11-15T23:00:00Z",
        "confirmed_utc": "2026-11-16T01:00:00Z"
      },
      "breakout_close_utc": "2026-11-16T06:00:00Z",
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": true,
      "valid_until_utc": "2026-11-17T13:00:00Z"
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
    "broker_symbol": "EURJPY",
    "tick_time_utc": "2026-11-16T13:01:11Z",
    "bid": 175.67,
    "ask": 175.682,
    "digits": 3,
    "point": 0.001,
    "spread_points": 12.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -0.0
  },
  "rtv": {
    "value": 1.0104448742746615,
    "baseline_median": 1292.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-16T13:00:00Z"
  }
}
```
