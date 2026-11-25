# USDCAD candidate evidence

JSON SHA-256: 2f1070ae7e0ee67517f68a7ed340b5ebf7c64e25e18dacf0d1953b41cd81f76d

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "USDCAD",
  "as_of_utc": "2026-11-25T02:45:00Z",
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
      "sha256": "98f02c8fb1769a8d2dfd336ef3c737cc031f2717a92ccd9b0973caf840c8f9ac",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-25T02:01:08Z",
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
      "sha256": "3a2c45b3f415b48966d0cabafcfeec06c5ed10c203c33470c8ed9b654f3ec56e",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-25T02:01:08Z",
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
      "sha256": "5f2f959cf88296b05aa016909831d6c865819f6789135d896ca21dfe4073cb4b",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-25T02:46:10Z",
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
      "last_closed_bar_utc": "2026-11-25T02:00:00Z",
      "close": 1.42693,
      "ema": {
        "20": 1.4319722033186457,
        "50": 1.429179661521109,
        "200": 1.417199622318774
      },
      "ema20_change_5bars": -0.0017045482998814254,
      "atr14": 0.0023910891268647573,
      "trend": "NEUTRAL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-25T02:00:00Z",
      "close": 1.42693,
      "ema": {
        "20": 1.4296817021190829,
        "50": 1.4318836278493796,
        "200": 1.429238635850585
      },
      "ema20_change_5bars": -0.0018687379991226827,
      "atr14": 0.0012594883382697228,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-25T02:45:00Z",
      "close": 1.42651,
      "ema": {
        "20": 1.426891964326846,
        "50": 1.4282530574522054,
        "200": 1.4318236395761004
      },
      "ema20_change_5bars": -0.00020188246168562074,
      "atr14": 0.000513157297334694,
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
    "tick_time_utc": "2026-11-25T02:46:09Z",
    "bid": 1.42657,
    "ask": 1.42667,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 10.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -2.1e-11
  },
  "rtv": {
    "value": 1.3333333333333333,
    "baseline_median": 376.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-25T02:45:00Z"
  }
}
```
