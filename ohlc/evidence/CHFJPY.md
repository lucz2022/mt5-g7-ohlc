# CHFJPY candidate evidence

JSON SHA-256: ffeaad99f89c0534ca499b67f87fe910f504e53f388531624e6d47e56511a342

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "CHFJPY",
  "as_of_utc": "2026-11-24T21:15:00Z",
  "price_basis": "BID",
  "status": "REJECT",
  "reasons": [
    "D1_H4_TREND_CONFLICT"
  ],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/CHFJPY/D1.json",
      "sha256": "557a16ed953bf2d117d4606c1b906624644180333d70014d6e1e279705b6f073",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CHFJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-24T03:31:11Z",
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
      "path": "ohlc/pairs/CHFJPY/H4.json",
      "sha256": "5d7cea7b602ab0eb401c0038ca1e1935f49430b4bf2d3a1e480dd5f80b9723d3",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CHFJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-24T18:01:16Z",
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
      "path": "ohlc/pairs/CHFJPY/H1.json",
      "sha256": "b6c1dea482e984aba05cb492435d8d9b455408560759f2b9d2ef1778e78c2679",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CHFJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-24T21:01:11Z",
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
      "path": "ohlc/pairs/CHFJPY/M15.json",
      "sha256": "d661d182d46d9f25f968c6e2b99e7175421941320c9400feb101170865a286fc",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CHFJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-24T21:16:16Z",
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
      "path": "ohlc/pairs/CHFJPY/W1.json",
      "sha256": "3219665e078c0b7c18a3526e834a971485ea5bd1b42228f652f3313afef1d1ae",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CHFJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-24T03:31:11Z",
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
      "close": 188.912,
      "ema": {
        "20": 190.52464941148978,
        "50": 191.48194386300972,
        "200": 194.33337378236592
      },
      "ema20_change_5bars": -0.980925466620846,
      "atr14": 1.130108358578393,
      "trend": "SELL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-24T18:00:00Z",
      "close": 190.586,
      "ema": {
        "20": 189.44569862150345,
        "50": 189.89381569382468,
        "200": 191.00209904446479
      },
      "ema20_change_5bars": 0.20031703386058552,
      "atr14": 0.5324809281106313,
      "trend": "NEUTRAL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-24T21:00:00Z",
      "close": 190.593,
      "ema": {
        "20": 189.9725891540669,
        "50": 189.56807993313174,
        "200": 189.90402751543115
      },
      "ema20_change_5bars": 0.4102002347572409,
      "atr14": 0.24401890684079244,
      "trend": "BUY"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-24T21:15:00Z",
      "close": 190.584,
      "ema": {
        "20": 190.54990452593302,
        "50": 190.22313097228468,
        "200": 189.56648597168694
      },
      "ema20_change_5bars": 0.033701271431681334,
      "atr14": 0.0905257426963932,
      "trend": "BUY"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-21T22:00:00Z",
      "close": 188.664,
      "ema": {
        "20": 193.09590454106697,
        "50": 193.88062865360095,
        "200": 174.95206456286553
      },
      "ema20_change_5bars": -1.6577180467520805,
      "atr14": 2.8955846156205403,
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
    "broker_symbol": "CHFJPY",
    "tick_time_utc": "2026-11-24T21:16:10Z",
    "bid": 190.584,
    "ask": 190.599,
    "digits": 3,
    "point": 0.001,
    "spread_points": 15.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": 1.4e-11
  },
  "rtv": {
    "value": 0.5544997205142538,
    "baseline_median": 894.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-24T21:15:00Z"
  }
}
```
