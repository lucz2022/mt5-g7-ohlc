# GBPUSD candidate evidence

JSON SHA-256: 17d9511bfced75c448f9990075d375f7bd5e5f3959b90aa5715f3894cc19995b

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "GBPUSD",
  "as_of_utc": "2026-11-16T10:00:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/GBPUSD/D1.json",
      "sha256": "3e515a24872c0df8323cf8b45473cb85c19a9f72dc4f7b709ff748b217355572",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPUSD",
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
      "path": "ohlc/pairs/GBPUSD/H4.json",
      "sha256": "b419b5232b535bf5cd55b4db274c2f46664bcbfbb1616d35a7394c86c2fa596d",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPUSD",
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
      "path": "ohlc/pairs/GBPUSD/H1.json",
      "sha256": "6f3aadecc01f4a5395de5e620814f0f05e0ff247e4a4122f37e5bd06cd317dec",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPUSD",
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
    "M15": {
      "path": "ohlc/pairs/GBPUSD/M15.json",
      "sha256": "381fe5ee3a2a9c0f569ef72439375ec045795a61b7a4c55ec1a3ce2c917752f4",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPUSD",
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
    "W1": {
      "path": "ohlc/pairs/GBPUSD/W1.json",
      "sha256": "75e24fe51244c56882a978d22ef62ca684220a36bd84dcb455be6f20d14cd65c",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T02:32:59Z",
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
      "close": 1.32116,
      "ema": {
        "20": 1.3335117413989181,
        "50": 1.335314065582684,
        "200": 1.3379687607724677
      },
      "ema20_change_5bars": -0.0028996793879985105,
      "atr14": 0.007599631130951889,
      "trend": "SELL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-16T10:00:00Z",
      "close": 1.3189,
      "ema": {
        "20": 1.3254068081475008,
        "50": 1.3313658539044968,
        "200": 1.3343971727258068
      },
      "ema20_change_5bars": -0.0031550007470613206,
      "atr14": 0.0026375183752015085,
      "trend": "SELL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T10:00:00Z",
      "close": 1.3189,
      "ema": {
        "20": 1.3211676453277847,
        "50": 1.3232934069039697,
        "200": 1.3315475430873083
      },
      "ema20_change_5bars": -0.0006022274482437862,
      "atr14": 0.0013755474062589197,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T10:00:00Z",
      "close": 1.3189,
      "ema": {
        "20": 1.3204192318562467,
        "50": 1.3208501809681015,
        "200": 1.323347678918684
      },
      "ema20_change_5bars": -0.0002713988589744254,
      "atr14": 0.0007398209844644432,
      "trend": "SELL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-14T22:00:00Z",
      "close": 1.32116,
      "ema": {
        "20": 1.336832598663811,
        "50": 1.3371038844414553,
        "200": 1.3134424165483185
      },
      "ema20_change_5bars": -0.0028835352773075584,
      "atr14": 0.016802691861221172,
      "trend": "SELL"
    }
  },
  "candidates": [
    {
      "symbol": "GBPUSD",
      "enabled": 0,
      "direction": "SELL",
      "mode": "BREAKOUT",
      "zone_low": 1.32031,
      "zone_high": 1.32073,
      "invalidation": 1.32107,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.75,
      "factor_group": "USD_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 1.025,
      "pivot": {
        "side": "LOW",
        "level": 1.3205200000000001,
        "index": 983,
        "confirmed_index": 985,
        "pivot_utc": "2026-11-13T18:00:00Z",
        "confirmed_utc": "2026-11-13T20:00:00Z"
      },
      "breakout_close_utc": "2026-11-16T10:00:00Z",
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": true,
      "valid_until_utc": "2026-11-17T10:00:00Z"
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
    "tick_time_utc": "2026-11-16T10:01:04Z",
    "bid": 1.31867,
    "ask": 1.31876,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 9.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": 8e-12
  },
  "rtv": {
    "value": 0.8440890919474586,
    "baseline_median": 875.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-16T10:00:00Z"
  }
}
```
