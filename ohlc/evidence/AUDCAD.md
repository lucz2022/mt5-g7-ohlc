# AUDCAD candidate evidence

JSON SHA-256: 3fdab1aa7050ddbc44672d2b1d620a160d76d325e9035bde54206ba597410922

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "AUDCAD",
  "as_of_utc": "2026-11-16T11:30:00Z",
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
      "sha256": "bf63b2cae5045ce4c26145d6a3fe5542f6b81fd77774f36855d646e2d2f5a167",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T10:01:12Z",
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
      "sha256": "f5a43766aa0fdcd78ccf08c572003fda6cf258859bf984eb9893214060faf4db",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T11:01:11Z",
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
      "sha256": "9fbb9151a228b15963499669ecc195eba98936126993093a0e6267b2b864f19d",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T11:31:12Z",
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
      "last_closed_bar_utc": "2026-11-16T10:00:00Z",
      "close": 0.96464,
      "ema": {
        "20": 0.9695288096712765,
        "50": 0.9729939325436852,
        "200": 0.9813216883283452
      },
      "ema20_change_5bars": -0.002766519104862808,
      "atr14": 0.002429597536276002,
      "trend": "SELL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T11:00:00Z",
      "close": 0.96459,
      "ema": {
        "20": 0.965902763670375,
        "50": 0.9681431780484391,
        "200": 0.9730210185333767
      },
      "ema20_change_5bars": -0.0007169762386279865,
      "atr14": 0.001228950401017673,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T11:30:00Z",
      "close": 0.96495,
      "ema": {
        "20": 0.9648657202902475,
        "50": 0.9653510731813579,
        "200": 0.9681529520213296
      },
      "ema20_change_5bars": -2.729219557007223e-05,
      "atr14": 0.0005238835074316667,
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
      "invalidation": 0.96608,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.5,
      "factor_group": "CAD_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 0.3743,
      "pivot": {
        "side": "HIGH",
        "level": 0.96559,
        "index": 997,
        "confirmed_index": 999,
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
      "valid_until_utc": "2026-11-17T11:30:00Z"
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
    "tick_time_utc": "2026-11-16T11:31:07Z",
    "bid": 0.96494,
    "ask": 0.96505,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 11.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": 6e-12
  },
  "rtv": {
    "value": 0.6536964980544747,
    "baseline_median": 899.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-16T11:30:00Z"
  }
}
```
