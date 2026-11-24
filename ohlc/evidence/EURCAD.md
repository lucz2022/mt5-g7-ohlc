# EURCAD candidate evidence

JSON SHA-256: 518cfa6ec85903cb2354fdc15eb24b95a529aeeceecf1811865fd43497df38f2

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "EURCAD",
  "as_of_utc": "2026-11-24T13:15:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/EURCAD/D1.json",
      "sha256": "8f9067f8b1e5f9a60cda0d3b38f5580e5cd91b5656a5d832d2477ff2989fb17b",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURCAD",
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
      "path": "ohlc/pairs/EURCAD/H4.json",
      "sha256": "0f2f3f64892ece53242b99c7a43be88e79b46994b3e2adc9fe5775d6bf4c103a",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T10:01:15Z",
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
      "path": "ohlc/pairs/EURCAD/H1.json",
      "sha256": "c3f9966c32fcc5597e8aa497b00632b661e0c411f383218aa945480b730113dc",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T13:01:11Z",
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
      "path": "ohlc/pairs/EURCAD/M15.json",
      "sha256": "931287f7ba13d1b95fa867fe4749394a36fbe3668136f5d3df67ca23ed07f82b",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T13:16:11Z",
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
      "path": "ohlc/pairs/EURCAD/W1.json",
      "sha256": "99e90a58fb51c6b5ea22ca92d5f43efe0490b6767ccc51ffe90da54f8bc6e9a1",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURCAD",
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
      "close": 1.5657299999999998,
      "ema": {
        "20": 1.574144664969496,
        "50": 1.583148667178645,
        "200": 1.5973106729538282
      },
      "ema20_change_5bars": -0.0020921431575551264,
      "atr14": 0.007288834042474914,
      "trend": "SELL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-24T10:00:00Z",
      "close": 1.5684,
      "ema": {
        "20": 1.570208108199844,
        "50": 1.5721320295274874,
        "200": 1.5784314522130434
      },
      "ema20_change_5bars": -0.0023264780210991987,
      "atr14": 0.0030893169005781957,
      "trend": "SELL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-24T13:00:00Z",
      "close": 1.5706099999999998,
      "ema": {
        "20": 1.5679347771663303,
        "50": 1.5692527552398636,
        "200": 1.572056278172715
      },
      "ema20_change_5bars": 0.0006526814101486256,
      "atr14": 0.0014493928793317182,
      "trend": "NEUTRAL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-24T13:15:00Z",
      "close": 1.5710899999999999,
      "ema": {
        "20": 1.5688405910260932,
        "50": 1.567854705736141,
        "200": 1.5692835584946618
      },
      "ema20_change_5bars": 0.0010055658715018012,
      "atr14": 0.0007509203495385564,
      "trend": "BUY"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-21T22:00:00Z",
      "close": 1.57317,
      "ema": {
        "20": 1.5915713276555947,
        "50": 1.5966538141924853,
        "200": 1.539260377918981
      },
      "ema20_change_5bars": -0.01397243246447366,
      "atr14": 0.01472361165771323,
      "trend": "SELL"
    }
  },
  "candidates": [
    {
      "symbol": "EURCAD",
      "enabled": 0,
      "direction": "SELL",
      "mode": "PULLBACK",
      "zone_low": 1.57251,
      "zone_high": 1.57295,
      "invalidation": 1.57331,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.5,
      "factor_group": "CAD_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 0.9797,
      "pivot": {
        "side": "HIGH",
        "level": 1.57273,
        "index": 975,
        "confirmed_index": 977,
        "pivot_utc": "2026-11-23T13:00:00Z",
        "confirmed_utc": "2026-11-23T15:00:00Z"
      },
      "breakout_close_utc": null,
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": false,
      "valid_until_utc": "2026-11-25T13:15:00Z"
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
    "broker_symbol": "EURCAD",
    "tick_time_utc": "2026-11-24T13:16:07Z",
    "bid": 1.57074,
    "ask": 1.57088,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 14.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -3e-12
  },
  "rtv": {
    "value": 1.3872590108968985,
    "baseline_median": 1193.0,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-24T13:15:00Z"
  }
}
```
