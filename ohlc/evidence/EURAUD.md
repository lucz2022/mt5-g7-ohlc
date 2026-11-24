# EURAUD candidate evidence

JSON SHA-256: cac46642bc0cae5a3a50f95fe6f3ef3777db616d5cea0f2d27dd68ad12ca5d3d

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "EURAUD",
  "as_of_utc": "2026-11-24T18:15:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/EURAUD/D1.json",
      "sha256": "ae494393136a92823b4a212966eb8015ea5bc2ebe74e43924390669e93477f9b",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURAUD",
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
      "path": "ohlc/pairs/EURAUD/H4.json",
      "sha256": "fc40d8ad86f7488ec729213b3e21542201924d08118ead1616a34b92c90dd77d",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURAUD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T18:01:15Z",
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
      "path": "ohlc/pairs/EURAUD/H1.json",
      "sha256": "5863d7311ca609c480578a8171af8427767cff81bf9e64645e890aad21e2a0ec",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURAUD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T18:01:14Z",
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
      "path": "ohlc/pairs/EURAUD/M15.json",
      "sha256": "c65c5b75aba0093ddf4c8e67d0081763c2bc3d253e0972c72c1cf1fbbeb1e5a2",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURAUD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T18:16:12Z",
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
      "path": "ohlc/pairs/EURAUD/W1.json",
      "sha256": "5d90e2588c4f5ea38f8e8a8d503898d1f85f05ae1be5d40023ede1cec333e6ba",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURAUD",
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
      "close": 1.64472,
      "ema": {
        "20": 1.6255864825951887,
        "50": 1.618901381371968,
        "200": 1.6417462394198723
      },
      "ema20_change_5bars": 0.012018571855960447,
      "atr14": 0.011333198048639415,
      "trend": "BUY"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-24T18:00:00Z",
      "close": 1.65183,
      "ema": {
        "20": 1.647076776105469,
        "50": 1.6391707516288296,
        "200": 1.6213326848043508
      },
      "ema20_change_5bars": 0.0015260392693721148,
      "atr14": 0.005405588533582269,
      "trend": "BUY"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-24T18:00:00Z",
      "close": 1.65183,
      "ema": {
        "20": 1.6493969510754207,
        "50": 1.6483963371626786,
        "200": 1.6388680101679238
      },
      "ema20_change_5bars": 0.00162308659581889,
      "atr14": 0.0030914405116506858,
      "trend": "BUY"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-24T18:15:00Z",
      "close": 1.6509,
      "ema": {
        "20": 1.651569634724838,
        "50": 1.6500329370535254,
        "200": 1.6483640189972877
      },
      "ema20_change_5bars": -5.016040829119994e-05,
      "atr14": 0.0016325296032394846,
      "trend": "NEUTRAL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-21T22:00:00Z",
      "close": 1.6565400000000001,
      "ema": {
        "20": 1.6247488759317235,
        "50": 1.6506128853063595,
        "200": 1.652351272763271
      },
      "ema20_change_5bars": -0.00296492727308717,
      "atr14": 0.021842628613531617,
      "trend": "NEUTRAL"
    }
  },
  "candidates": [
    {
      "symbol": "EURAUD",
      "enabled": 0,
      "direction": "BUY",
      "mode": "PULLBACK",
      "zone_low": 1.64807,
      "zone_high": 1.64899,
      "invalidation": 1.6473,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.5,
      "factor_group": "EUR_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 0.6178,
      "pivot": {
        "side": "LOW",
        "level": 1.64853,
        "index": 997,
        "confirmed_index": 999,
        "pivot_utc": "2026-11-24T16:00:00Z",
        "confirmed_utc": "2026-11-24T18:00:00Z"
      },
      "breakout_close_utc": null,
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": false,
      "valid_until_utc": "2026-11-25T18:15:00Z"
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
    "broker_symbol": "EURAUD",
    "tick_time_utc": "2026-11-24T18:16:09Z",
    "bid": 1.65088,
    "ask": 1.65102,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 14.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -3e-12
  },
  "rtv": {
    "value": 0.6599721059972106,
    "baseline_median": 1792.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-24T18:15:00Z"
  }
}
```
