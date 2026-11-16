# USDJPY candidate evidence

JSON SHA-256: a3225cb5259a6df254575e4dbf7ef497718c4ef7a6a4f2a8a9b8ae6891092a06

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "USDJPY",
  "as_of_utc": "2026-11-16T10:30:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/USDJPY/D1.json",
      "sha256": "9f66f19f2ea1d1b362ad35a5e1954679e3b7dc8cee67f07f07de10927c8c0735",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T02:38:22Z",
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
      "path": "ohlc/pairs/USDJPY/H4.json",
      "sha256": "62dbf4bff96cfabe99ea8094961419b9cd2cbdbfffe030eb0718ccf73511ad4a",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T10:01:09Z",
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
      "path": "ohlc/pairs/USDJPY/H1.json",
      "sha256": "486c4b37f2262f977cca1241686851fc21df8f5f50a3c7d478561e886a7c59d1",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T10:01:08Z",
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
      "path": "ohlc/pairs/USDJPY/M15.json",
      "sha256": "31f1a3b303d388fa3186b2c9ccbe6644e4aec673a3357c45bf5672fd7bf7f392",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T10:31:09Z",
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
      "path": "ohlc/pairs/USDJPY/W1.json",
      "sha256": "2d356cd5f619b7870c634390d2ceb63dd5f50314f01b8cc8903246cc629fcc98",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T02:33:03Z",
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
      "close": 159.666,
      "ema": {
        "20": 158.4644052436213,
        "50": 158.21089731732985,
        "200": 157.86590998799457
      },
      "ema20_change_5bars": 0.5312894312571927,
      "atr14": 0.9380352134708385,
      "trend": "BUY"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-16T10:00:00Z",
      "close": 159.567,
      "ema": {
        "20": 159.51794244792367,
        "50": 158.9839905107962,
        "200": 158.23096133323259
      },
      "ema20_change_5bars": 0.08273679035201553,
      "atr14": 0.3345351573502705,
      "trend": "BUY"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T10:00:00Z",
      "close": 159.567,
      "ema": {
        "20": 159.66260227940595,
        "50": 159.66448461298313,
        "200": 158.97469705545163
      },
      "ema20_change_5bars": -0.09975558751457925,
      "atr14": 0.1815438595680056,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T10:30:00Z",
      "close": 159.641,
      "ema": {
        "20": 159.53849883416905,
        "50": 159.60235390847222,
        "200": 159.66074274156153
      },
      "ema20_change_5bars": 0.023873345798591572,
      "atr14": 0.09562039391087843,
      "trend": "NEUTRAL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-14T22:00:00Z",
      "close": 159.666,
      "ema": {
        "20": 158.2803507432631,
        "50": 157.2459979431644,
        "200": 147.22575514765515
      },
      "ema20_change_5bars": -0.04434810719143911,
      "atr14": 2.3506444471435506,
      "trend": "NEUTRAL"
    }
  },
  "candidates": [
    {
      "symbol": "USDJPY",
      "enabled": 0,
      "direction": "BUY",
      "mode": "PULLBACK",
      "zone_low": 159.298,
      "zone_high": 159.352,
      "invalidation": 159.253,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.75,
      "factor_group": "USD_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 1.5919,
      "pivot": {
        "side": "LOW",
        "level": 159.325,
        "index": 958,
        "confirmed_index": 960,
        "pivot_utc": "2026-11-12T17:00:00Z",
        "confirmed_utc": "2026-11-12T19:00:00Z"
      },
      "breakout_close_utc": null,
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": false,
      "valid_until_utc": "2026-11-17T10:30:00Z"
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
    "broker_symbol": "USDJPY",
    "tick_time_utc": "2026-11-16T10:31:06Z",
    "bid": 159.622,
    "ask": 159.631,
    "digits": 3,
    "point": 0.001,
    "spread_points": 9.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": 1.4e-11
  },
  "rtv": {
    "value": 0.7612317011610298,
    "baseline_median": 990.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-16T10:30:00Z"
  }
}
```
