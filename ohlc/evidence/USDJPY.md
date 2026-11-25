# USDJPY candidate evidence

JSON SHA-256: 4e09aa74872c2e44cc30a235eac47123ff91bbaaba75174d0cb7336ca819ed26

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "USDJPY",
  "as_of_utc": "2026-11-25T01:00:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/USDJPY/D1.json",
      "sha256": "4c1c6889ae7d5420c5d3a77fd6f2a2bf1ff6bd53e612e829bb4aec1de4552a39",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-24T22:01:15Z",
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
      "sha256": "50513bd5d6a5879a8cc1c3b2709d62cdcc512b856df40305aba132a4abe864bf",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-24T22:01:15Z",
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
      "sha256": "fe08775f532d9e79c208ea173b2e6c414633205e6e7a734de4cf8461cd3d6f2c",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-25T01:01:08Z",
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
      "sha256": "28bc6eb939c6e1b334dfeb7d95df96681b34f856a737d857848dd490cdccc528",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-25T01:01:08Z",
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
      "sha256": "0daf268f91764c0cb7aa8f3c1c5d08ae1348db1f724ddf622a1f5d47ae0c0c69",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDJPY",
      "digits": 3,
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
      "close": 159.247,
      "ema": {
        "20": 158.83265740062717,
        "50": 158.4555281097186,
        "200": 157.9495776116681
      },
      "ema20_change_5bars": 0.19965446877392878,
      "atr14": 0.9013335498749152,
      "trend": "BUY"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-24T22:00:00Z",
      "close": 159.247,
      "ema": {
        "20": 159.17875106856198,
        "50": 159.16448758443929,
        "200": 158.55569894447348
      },
      "ema20_change_5bars": 0.05460295741414711,
      "atr14": 0.35831645091653336,
      "trend": "BUY"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-25T01:00:00Z",
      "close": 159.244,
      "ema": {
        "20": 159.20826347394816,
        "50": 159.16590634953727,
        "200": 159.1715161979329
      },
      "ema20_change_5bars": 0.028364901954432753,
      "atr14": 0.15732711752940132,
      "trend": "BUY"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-25T01:00:00Z",
      "close": 159.244,
      "ema": {
        "20": 159.25424389619621,
        "50": 159.23323691054472,
        "200": 159.16465346324304
      },
      "ema20_change_5bars": 0.007011270724063934,
      "atr14": 0.07453537059666265,
      "trend": "BUY"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-21T22:00:00Z",
      "close": 158.556,
      "ema": {
        "20": 158.30660305342863,
        "50": 157.29737198336252,
        "200": 147.350222460138
      },
      "ema20_change_5bars": 0.01673266492198877,
      "atr14": 2.293741272331575,
      "trend": "BUY"
    }
  },
  "candidates": [
    {
      "symbol": "USDJPY",
      "enabled": 0,
      "direction": "BUY",
      "mode": "PULLBACK",
      "zone_low": 159.145,
      "zone_high": 159.193,
      "invalidation": 159.106,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.75,
      "factor_group": "USD_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 0.3242,
      "pivot": {
        "side": "LOW",
        "level": 159.169,
        "index": 995,
        "confirmed_index": 997,
        "pivot_utc": "2026-11-24T21:00:00Z",
        "confirmed_utc": "2026-11-24T23:00:00Z"
      },
      "breakout_close_utc": null,
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": true,
      "valid_until_utc": "2026-11-26T01:00:00Z"
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
    "tick_time_utc": "2026-11-25T01:01:07Z",
    "bid": 159.253,
    "ask": 159.262,
    "digits": 3,
    "point": 0.001,
    "spread_points": 9.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -1.5e-11
  },
  "rtv": {
    "value": 2.9026063100137174,
    "baseline_median": 364.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-25T01:00:00Z"
  }
}
```
