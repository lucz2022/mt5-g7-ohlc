# AUDJPY candidate evidence

JSON SHA-256: 502d48e2ca851b01002aea042861898a43984899a4b8a2e72e7bc54b5408bc3a

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "AUDJPY",
  "as_of_utc": "2026-11-16T18:00:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/AUDJPY/D1.json",
      "sha256": "9e8800230d50e1eaef91031b7b665bfe1ec23da89c7bb655d31f404ed846c248",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDJPY",
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
      "path": "ohlc/pairs/AUDJPY/H4.json",
      "sha256": "ed3fc6bbc1aa018ba46667b3b58faf65c36c87bbdfc28d3f5532405885878c38",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T18:01:10Z",
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
      "sha256": "1b8074440b2b18e6ff02857e0fa399d2507c595b208df433d7fc66f856458fc6",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T18:01:09Z",
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
      "sha256": "52afafa3119317d830ab445cd617db694fc8934a83d05f5cb162de0fef8ba44c",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T18:01:09Z",
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
      "last_closed_bar_utc": "2026-11-13T22:00:00Z",
      "close": 108.106,
      "ema": {
        "20": 109.77058366943058,
        "50": 110.50869110133104,
        "200": 110.10590981790173
      },
      "ema20_change_5bars": -0.5746653068442384,
      "atr14": 0.9586381385397111,
      "trend": "SELL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-16T18:00:00Z",
      "close": 107.61,
      "ema": {
        "20": 108.43609486796895,
        "50": 109.05613724923869,
        "200": 110.08327410571273
      },
      "ema20_change_5bars": -0.4405699157763223,
      "atr14": 0.3637986927766915,
      "trend": "SELL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T18:00:00Z",
      "close": 107.61,
      "ema": {
        "20": 107.87399699715968,
        "50": 108.23682226669258,
        "200": 109.07973690952373
      },
      "ema20_change_5bars": -0.12370662054577508,
      "atr14": 0.18208093657079227,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T18:00:00Z",
      "close": 107.61,
      "ema": {
        "20": 107.70248878852007,
        "50": 107.78142774494005,
        "200": 108.24503082146363
      },
      "ema20_change_5bars": -0.012226931523287021,
      "atr14": 0.08262848317327057,
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
      "zone_low": 107.629,
      "zone_high": 107.683,
      "invalidation": 107.729,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.5,
      "factor_group": "JPY_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 0.1043,
      "pivot": {
        "side": "LOW",
        "level": 107.656,
        "index": 991,
        "confirmed_index": 993,
        "pivot_utc": "2026-11-16T10:00:00Z",
        "confirmed_utc": "2026-11-16T12:00:00Z"
      },
      "breakout_close_utc": "2026-11-16T18:00:00Z",
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": true,
      "valid_until_utc": "2026-11-17T18:00:00Z"
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
    "tick_time_utc": "2026-11-16T18:01:07Z",
    "bid": 107.566,
    "ask": 107.579,
    "digits": 3,
    "point": 0.001,
    "spread_points": 13.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": 9e-12
  },
  "rtv": {
    "value": 0.8524212144504227,
    "baseline_median": 1301.0,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-16T18:00:00Z"
  }
}
```
