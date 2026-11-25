# AUDJPY candidate evidence

JSON SHA-256: c3bc94dc05502f49a3090c6ab278c7f3cacdbb96a401e5e460a7c4e797fc854b

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "AUDJPY",
  "as_of_utc": "2026-11-25T07:45:00Z",
  "price_basis": "BID",
  "status": "WATCH",
  "reasons": [
    "NO_VALID_NEARBY_ZONE"
  ],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/AUDJPY/D1.json",
      "sha256": "28c09fa579b40c8ce05f843ccbb9745223ff9b11335cc517d878365324310258",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-24T22:01:30Z",
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
      "sha256": "677262d6320a42264705cd7f5984bf0f783a49c310ecfbe83e9b27f94274b3f3",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-25T06:01:12Z",
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
      "sha256": "78e84973eefee2be9a0bee3af21f95ee8e8aeae3e884cb70d9b69fd67cb2ebd0",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-25T07:01:10Z",
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
      "sha256": "bc9a42aeaae5e1fdeeed07cf38a66968397fe15fe91d0f7ed1a00a223d07a7a4",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-25T07:46:13Z",
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
      "sha256": "7205e83b1756cb395f01e7d609086941aaf122958a93ec4eb7ffaba9fa414cfc",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-24T03:31:09Z",
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
      "close": 105.74,
      "ema": {
        "20": 107.93792215042521,
        "50": 109.4616562130564,
        "200": 109.83815424215601
      },
      "ema20_change_5bars": -1.3954762728501606,
      "atr14": 1.0236253544518101,
      "trend": "SELL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-25T06:00:00Z",
      "close": 105.048,
      "ema": {
        "20": 105.76761871319091,
        "50": 106.64710564036099,
        "200": 108.84410729637796
      },
      "ema20_change_5bars": -0.14199049797622365,
      "atr14": 0.5086610704072098,
      "trend": "SELL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-25T07:00:00Z",
      "close": 104.753,
      "ema": {
        "20": 105.43785698845377,
        "50": 105.5771083266118,
        "200": 106.65412764219033
      },
      "ema20_change_5bars": -0.2544265189508508,
      "atr14": 0.27499865448812955,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-25T07:45:00Z",
      "close": 104.491,
      "ema": {
        "20": 104.99827121311495,
        "50": 105.29809947836046,
        "200": 105.56121029771816
      },
      "ema20_change_5bars": -0.23412724823651843,
      "atr14": 0.14143258753436613,
      "trend": "SELL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-21T22:00:00Z",
      "close": 104.899,
      "ema": {
        "20": 110.20067155248472,
        "50": 109.01396541666064,
        "200": 100.36292178885488
      },
      "ema20_change_5bars": -1.2361484996111045,
      "atr14": 2.1906751695513464,
      "trend": "NEUTRAL"
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
    "broker_symbol": "AUDJPY",
    "tick_time_utc": "2026-11-25T07:46:09Z",
    "bid": 104.463,
    "ask": 104.476,
    "digits": 3,
    "point": 0.001,
    "spread_points": 13.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -5e-12
  },
  "rtv": {
    "value": 1.4942723801442512,
    "baseline_median": 1178.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-25T07:45:00Z"
  }
}
```
