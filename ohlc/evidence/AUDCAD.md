# AUDCAD candidate evidence

JSON SHA-256: f026e3816a933ac4a8479f2e1449105d3d399edfd51c9945f1bacad75e8ca08c

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "AUDCAD",
  "as_of_utc": "2026-11-16T15:30:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/AUDCAD/D1.json",
      "sha256": "e6b2ec98debef3a35a5a728602c9aa4060517b0722bb3bd30976f0805d4d5bf3",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T02:51:54Z",
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
      "path": "ohlc/pairs/AUDCAD/H4.json",
      "sha256": "383e2200b56a2f6231c64f9503f0c4bfd202185244c6450d8ac6b9df6690c7d9",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T14:01:13Z",
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
      "path": "ohlc/pairs/AUDCAD/H1.json",
      "sha256": "f6a03e0c9b8897114250fe7990a60a73dc7eecfbe5a3b6b22d0968a126f175b2",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T15:01:13Z",
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
      "path": "ohlc/pairs/AUDCAD/M15.json",
      "sha256": "a72899caff08f552ac437133a00a322af7ca4b71f3f92903c7fa639ab756f391",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T15:31:14Z",
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
      "path": "ohlc/pairs/AUDCAD/W1.json",
      "sha256": "672d7f48aeb4ad7d2a079fdb5707419fa227de4627c3bfb0f77235d66ae01432",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T02:51:54Z",
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
      "close": 0.96598,
      "ema": {
        "20": 0.9781513096646682,
        "50": 0.9835476108865372,
        "200": 0.9744559049185194
      },
      "ema20_change_5bars": -0.003823978913365722,
      "atr14": 0.006380966741112157,
      "trend": "SELL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-16T14:00:00Z",
      "close": 0.96513,
      "ema": {
        "20": 0.9691098754168692,
        "50": 0.9726855430314004,
        "200": 0.9811583253077814
      },
      "ema20_change_5bars": -0.0026468506186854146,
      "atr14": 0.0023753405693991408,
      "trend": "SELL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T15:00:00Z",
      "close": 0.96451,
      "ema": {
        "20": 0.9655708844786224,
        "50": 0.9676639087703114,
        "200": 0.9727027962731303
      },
      "ema20_change_5bars": -0.0004700648412657715,
      "atr14": 0.0011847959809315246,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T15:30:00Z",
      "close": 0.96458,
      "ema": {
        "20": 0.9648443455678813,
        "50": 0.9651157455274664,
        "200": 0.9676654358397941
      },
      "ema20_change_5bars": -9.035865764828177e-05,
      "atr14": 0.0006210140688738012,
      "trend": "SELL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-14T22:00:00Z",
      "close": 0.96598,
      "ema": {
        "20": 0.982517587436579,
        "50": 0.9685031306479549,
        "200": 0.9316592543763276
      },
      "ema20_change_5bars": -0.004188880054147193,
      "atr14": 0.012198720241406624,
      "trend": "NEUTRAL"
    }
  },
  "candidates": [
    {
      "symbol": "AUDCAD",
      "enabled": 0,
      "direction": "SELL",
      "mode": "PULLBACK",
      "zone_low": 0.96541,
      "zone_high": 0.96577,
      "invalidation": 0.96607,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.5,
      "factor_group": "CAD_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 0.7005,
      "pivot": {
        "side": "HIGH",
        "level": 0.96559,
        "index": 993,
        "confirmed_index": 995,
        "pivot_utc": "2026-11-16T09:00:00Z",
        "confirmed_utc": "2026-11-16T11:00:00Z"
      },
      "breakout_close_utc": null,
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": true,
      "valid_until_utc": "2026-11-17T15:30:00Z"
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
    "broker_symbol": "AUDCAD",
    "tick_time_utc": "2026-11-16T15:31:08Z",
    "bid": 0.96451,
    "ask": 0.96464,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 13.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -7e-12
  },
  "rtv": {
    "value": 1.3876063183475091,
    "baseline_median": 823.0,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-16T15:30:00Z"
  }
}
```
