# EURUSD candidate evidence

JSON SHA-256: 7537f377e38741de493604ba013f44c9b705413bb0790ca2e671dcb13081b6d2

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "EURUSD",
  "as_of_utc": "2026-11-24T20:30:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/EURUSD/D1.json",
      "sha256": "5fd30c7614d9a2df5a7ae7d2fc9aae9a6e1a55f0a62d0e8f8e2d8ffd22afbd87",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T03:31:07Z",
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
      "sha256": "7d9a9e9000a1ccd5a9d8a941affb314ebc1c3c87cee92e94f25948ac00cf746c",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T18:01:12Z",
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
      "sha256": "c1cededc70deac4ad2dfdcf26a2e1e2c86aa032f98238e319c4cfaf2232b5526",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T20:01:06Z",
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
      "sha256": "fbf5927b8ed23b46e74cac2f25f5e4743e05434f6d19cdfbebf9cd57f6f18113",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T20:31:07Z",
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
      "sha256": "c536aa181fdb94de842cbad195bee9f2ee50d6697d6f3ef7ff5d68642b641f36",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T03:31:07Z",
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
      "close": 1.09023,
      "ema": {
        "20": 1.1074089882777365,
        "50": 1.12024151825103,
        "200": 1.1414669305063567
      },
      "ema20_change_5bars": -0.007582252215511787,
      "atr14": 0.006748250083318013,
      "trend": "SELL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-24T18:00:00Z",
      "close": 1.09733,
      "ema": {
        "20": 1.0955599630116717,
        "50": 1.099810735504378,
        "200": 1.113991349163556
      },
      "ema20_change_5bars": -0.0008331179822353985,
      "atr14": 0.002867816100418666,
      "trend": "SELL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-24T20:00:00Z",
      "close": 1.09659,
      "ema": {
        "20": 1.0948276866037678,
        "50": 1.0947108794123575,
        "200": 1.099731427219765
      },
      "ema20_change_5bars": 0.00130830281251626,
      "atr14": 0.001223004850776723,
      "trend": "BUY"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-24T20:30:00Z",
      "close": 1.0967,
      "ema": {
        "20": 1.0966370459476282,
        "50": 1.0955473355116379,
        "200": 1.094702092887205
      },
      "ema20_change_5bars": 2.085901336013052e-05,
      "atr14": 0.0005234108928552341,
      "trend": "BUY"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-21T22:00:00Z",
      "close": 1.09653,
      "ema": {
        "20": 1.1313730312189925,
        "50": 1.1431349861403015,
        "200": 1.1264673937408674
      },
      "ema20_change_5bars": -0.01487055574361218,
      "atr14": 0.013123070373261266,
      "trend": "SELL"
    }
  },
  "candidates": [
    {
      "symbol": "EURUSD",
      "enabled": 0,
      "direction": "SELL",
      "mode": "PULLBACK",
      "zone_low": 1.09784,
      "zone_high": 1.0982,
      "invalidation": 1.09851,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.75,
      "factor_group": "USD_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 0.9321,
      "pivot": {
        "side": "HIGH",
        "level": 1.09802,
        "index": 994,
        "confirmed_index": 996,
        "pivot_utc": "2026-11-24T15:00:00Z",
        "confirmed_utc": "2026-11-24T17:00:00Z"
      },
      "breakout_close_utc": null,
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": false,
      "valid_until_utc": "2026-11-25T20:30:00Z"
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
    "tick_time_utc": "2026-11-24T20:31:04Z",
    "bid": 1.0967,
    "ask": 1.09679,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 9.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": 8e-12
  },
  "rtv": {
    "value": 0.42488888888888887,
    "baseline_median": 562.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-24T20:30:00Z"
  }
}
```
