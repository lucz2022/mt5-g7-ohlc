# GBPUSD candidate evidence

JSON SHA-256: 1c3032c8437b6313e2d7b02cf2b07316719d8e5968ea6f3caf0677b4064ebceb

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "GBPUSD",
  "as_of_utc": "2026-11-24T22:15:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/GBPUSD/D1.json",
      "sha256": "ad246c2dcc8177b4bd87f54446980115415ad121e4a13fc174be6b452c0ddcdf",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T22:01:12Z",
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
      "path": "ohlc/pairs/GBPUSD/H4.json",
      "sha256": "30429541f8950d58764eddac110506ec8275993075f23e41fc24b009df36ab6d",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T22:01:12Z",
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
      "path": "ohlc/pairs/GBPUSD/H1.json",
      "sha256": "33746e15aacb94997b0cd89f2db92647f5499acd50e210c5a7ed2eb75552a629",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T22:01:12Z",
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
      "path": "ohlc/pairs/GBPUSD/M15.json",
      "sha256": "5868f47cbf6cbdcf0e77b8f8e2f5e4ef6a4bea484222d8381616bb6125de4979",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T22:16:10Z",
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
      "path": "ohlc/pairs/GBPUSD/W1.json",
      "sha256": "798f5481b0b05e4fbc0b0a97f906282eaa21bb948bf0416fa82f50a013658390",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPUSD",
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
      "close": 1.31144,
      "ema": {
        "20": 1.3223449311783997,
        "50": 1.3295830120104577,
        "200": 1.336234692957017
      },
      "ema20_change_5bars": -0.008647492052914263,
      "atr14": 0.00787456596618081,
      "trend": "SELL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-24T22:00:00Z",
      "close": 1.31144,
      "ema": {
        "20": 1.3096969165039876,
        "50": 1.3154293039608493,
        "200": 1.3275019213984645
      },
      "ema20_change_5bars": -0.00029886885469654345,
      "atr14": 0.003033500035926284,
      "trend": "SELL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-24T22:00:00Z",
      "close": 1.31144,
      "ema": {
        "20": 1.309193631497184,
        "50": 1.308550081798569,
        "200": 1.3154392147413383
      },
      "ema20_change_5bars": 0.0015836478368858042,
      "atr14": 0.0012894103199487473,
      "trend": "BUY"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-24T22:15:00Z",
      "close": 1.31115,
      "ema": {
        "20": 1.3113756153733807,
        "50": 1.3101161761028595,
        "200": 1.308510529474234
      },
      "ema20_change_5bars": -1.697538411304933e-05,
      "atr14": 0.00049355272684468,
      "trend": "NEUTRAL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-21T22:00:00Z",
      "close": 1.30804,
      "ema": {
        "20": 1.3340904464101146,
        "50": 1.3359641189399871,
        "200": 1.313212187018977
      },
      "ema20_change_5bars": -0.004948912869944921,
      "atr14": 0.016688213870419927,
      "trend": "SELL"
    }
  },
  "candidates": [
    {
      "symbol": "GBPUSD",
      "enabled": 0,
      "direction": "SELL",
      "mode": "PULLBACK",
      "zone_low": 1.31221,
      "zone_high": 1.31259,
      "invalidation": 1.31291,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.75,
      "factor_group": "USD_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 0.8221,
      "pivot": {
        "side": "HIGH",
        "level": 1.3124,
        "index": 996,
        "confirmed_index": 998,
        "pivot_utc": "2026-11-24T19:00:00Z",
        "confirmed_utc": "2026-11-24T21:00:00Z"
      },
      "breakout_close_utc": null,
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": false,
      "valid_until_utc": "2026-11-25T22:15:00Z"
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
    "broker_symbol": "GBPUSD",
    "tick_time_utc": "2026-11-24T22:16:04Z",
    "bid": 1.31111,
    "ask": 1.31154,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 43.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": 7e-12
  },
  "rtv": {
    "value": 0.039032006245121,
    "baseline_median": 640.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-24T22:15:00Z"
  }
}
```
