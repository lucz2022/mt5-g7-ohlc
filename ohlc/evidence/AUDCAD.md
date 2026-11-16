# AUDCAD candidate evidence

JSON SHA-256: 0b8ecf710c2e2647e8a28ebd775e0e3dff6423ada6ce9843a1f699769ea2aaf9

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "AUDCAD",
  "as_of_utc": "2026-11-16T06:15:00Z",
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
      "sha256": "36930dd7924f80c526f81535688bb4570d1a0e5b19160e94196ba244dab25609",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T06:01:12Z",
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
      "sha256": "6db6090ec2fc34a169a979af4901cc67498787df2dfcbd421c239aa461bfb24b",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T06:01:12Z",
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
      "sha256": "0c7f4490188eab75e295370ff3e2adb5c58a53d70d1c4542cdefd6b2d1b3169d",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T06:16:11Z",
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
      "last_closed_bar_utc": "2026-11-16T06:00:00Z",
      "close": 0.96403,
      "ema": {
        "20": 0.9700434212156214,
        "50": 0.9733349093839009,
        "200": 0.9814923244323805
      },
      "ema20_change_5bars": -0.002739836905374715,
      "atr14": 0.0024541819621433907,
      "trend": "SELL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T06:00:00Z",
      "close": 0.96403,
      "ema": {
        "20": 0.966619739909003,
        "50": 0.9688819489712543,
        "200": 0.9734419317274773
      },
      "ema20_change_5bars": -0.0008852073738394584,
      "atr14": 0.001253934521999954,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T06:15:00Z",
      "close": 0.9636,
      "ema": {
        "20": 0.9652930993627482,
        "50": 0.9660728129660051,
        "200": 0.9689365802216645
      },
      "ema20_change_5bars": -0.0006974178421370603,
      "atr14": 0.0006275231835888925,
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
      "mode": "BREAKOUT",
      "zone_low": 0.96474,
      "zone_high": 0.96512,
      "invalidation": 0.96543,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.5,
      "factor_group": "CAD_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 0.9091,
      "pivot": {
        "side": "LOW",
        "level": 0.96493,
        "index": 995,
        "confirmed_index": 997,
        "pivot_utc": "2026-11-16T02:00:00Z",
        "confirmed_utc": "2026-11-16T04:00:00Z"
      },
      "breakout_close_utc": "2026-11-16T06:00:00Z",
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": true,
      "valid_until_utc": "2026-11-17T06:15:00Z"
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
    "tick_time_utc": "2026-11-16T06:16:07Z",
    "bid": 0.96353,
    "ask": 0.96364,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 11.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -5e-12
  },
  "rtv": {
    "value": 1.0736842105263158,
    "baseline_median": 902.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-16T06:15:00Z"
  }
}
```
