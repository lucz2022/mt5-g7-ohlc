# EURUSD candidate evidence

JSON SHA-256: dfc1b0bbe5feb1ac0d38dfbbba90cfb5691425363afdfc1ffeb0a7663a3b5b7a

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "EURUSD",
  "as_of_utc": "2026-11-16T11:15:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/EURUSD/D1.json",
      "sha256": "e22a8a821e18d76f7be9b854e6e2607026524ca553f4be5bb958762e12f0f4de",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURUSD",
      "digits": 5,
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
      "path": "ohlc/pairs/EURUSD/H4.json",
      "sha256": "9983863cdcb376afa7d0212b3d47f318614ebd78962f87683ad1806944897831",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURUSD",
      "digits": 5,
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
    "H1": {
      "path": "ohlc/pairs/EURUSD/H1.json",
      "sha256": "a1a2ee4b9f2d0025a34c60dbf2ea074533cdacdc200146f051c281edc64f38a5",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T11:01:08Z",
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
      "path": "ohlc/pairs/EURUSD/M15.json",
      "sha256": "739438265df804f0bf46590a6c1b65646d74e21348c29964e301a8f85c3980b3",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T11:16:07Z",
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
      "path": "ohlc/pairs/EURUSD/W1.json",
      "sha256": "0ec3efabd293333b8c28d6b2c3f4ff96e68d027f42748fcdd07f141bf2c75d35",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T02:32:56Z",
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
      "close": 1.10221,
      "ema": {
        "20": 1.1165987394925376,
        "50": 1.1266710599509253,
        "200": 1.1442348486627871
      },
      "ema20_change_5bars": -0.004226333414568018,
      "atr14": 0.006997881258476543,
      "trend": "SELL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-16T10:00:00Z",
      "close": 1.10096,
      "ema": {
        "20": 1.106882059956895,
        "50": 1.1120865648047953,
        "200": 1.1216370600945647
      },
      "ema20_change_5bars": -0.0031620083344030547,
      "atr14": 0.0022302569992013912,
      "trend": "SELL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T11:00:00Z",
      "close": 1.10047,
      "ema": {
        "20": 1.10238203317597,
        "50": 1.104710420384484,
        "200": 1.112107249365083
      },
      "ema20_change_5bars": -0.0006869740713217887,
      "atr14": 0.001114345163667021,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T11:15:00Z",
      "close": 1.10053,
      "ema": {
        "20": 1.101350316962433,
        "50": 1.1018669520994373,
        "200": 1.104721095730876
      },
      "ema20_change_5bars": -0.00034378884536745424,
      "atr14": 0.0005686803196449944,
      "trend": "SELL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-14T22:00:00Z",
      "close": 1.10221,
      "ema": {
        "20": 1.1350407187157285,
        "50": 1.1450372395071322,
        "200": 1.1268826106354939
      },
      "ema20_change_5bars": -0.013559035295571231,
      "atr14": 0.013538691171356216,
      "trend": "SELL"
    }
  },
  "candidates": [
    {
      "symbol": "EURUSD",
      "enabled": 0,
      "direction": "SELL",
      "mode": "BREAKOUT",
      "zone_low": 1.10178,
      "zone_high": 1.10212,
      "invalidation": 1.1024,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.75,
      "factor_group": "USD_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 1.1217,
      "pivot": {
        "side": "LOW",
        "level": 1.10195,
        "index": 986,
        "confirmed_index": 988,
        "pivot_utc": "2026-11-13T22:00:00Z",
        "confirmed_utc": "2026-11-16T00:00:00Z"
      },
      "breakout_close_utc": "2026-11-16T10:00:00Z",
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": true,
      "valid_until_utc": "2026-11-17T11:15:00Z"
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
    "broker_symbol": "EURUSD",
    "tick_time_utc": "2026-11-16T11:16:07Z",
    "bid": 1.10037,
    "ask": 1.10046,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 9.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": 8e-12
  },
  "rtv": {
    "value": 1.2704663212435232,
    "baseline_median": 482.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-16T11:15:00Z"
  }
}
```
