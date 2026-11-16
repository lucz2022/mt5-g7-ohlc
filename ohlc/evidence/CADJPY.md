# CADJPY candidate evidence

JSON SHA-256: 3534d2ca4ac497920c255ac3e555e403b086b2167451eb1999071ba76f0c8901

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "CADJPY",
  "as_of_utc": "2026-11-16T21:45:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/CADJPY/D1.json",
      "sha256": "65f717deae2fe45ff4ef5c663c01001f2a5938a2daa57bf3e47ed6d9d633fb31",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CADJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T02:38:23Z",
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
      "path": "ohlc/pairs/CADJPY/H4.json",
      "sha256": "aa44af19b1b065d2f96ace6a33f1aacccc311f4fff15d1bbd6ffcc3e436d306b",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CADJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T18:01:10Z",
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
      "path": "ohlc/pairs/CADJPY/H1.json",
      "sha256": "0969879e11e24e7423b7326b5b482698835cdc13bb1d607c6f879cb65442e7e5",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CADJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T21:01:10Z",
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
      "path": "ohlc/pairs/CADJPY/M15.json",
      "sha256": "00ce7ed988e52df4e79b37348a79d6e054e9d04173d0b649a26646a16b8dfc70",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CADJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T21:46:24Z",
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
      "path": "ohlc/pairs/CADJPY/W1.json",
      "sha256": "1bcab963658df647c46e63689a363181e09e3f0e63e3c4f64c4c5e4a4c61cdd6",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CADJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T02:34:28Z",
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
      "close": 111.879,
      "ema": {
        "20": 112.2132386127794,
        "50": 112.34992226058512,
        "200": 112.94552668328471
      },
      "ema20_change_5bars": -0.15335660966159992,
      "atr14": 0.6603116595513316,
      "trend": "SELL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-16T18:00:00Z",
      "close": 111.57,
      "ema": {
        "20": 111.93910757999006,
        "50": 112.1515898710006,
        "200": 112.21591001477725
      },
      "ema20_change_5bars": -0.16058466516855674,
      "atr14": 0.2533563076143924,
      "trend": "SELL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T21:00:00Z",
      "close": 111.527,
      "ema": {
        "20": 111.6843263213991,
        "50": 111.84512693062558,
        "200": 112.14330206864666
      },
      "ema20_change_5bars": -0.08081871341265412,
      "atr14": 0.12680885897503832,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T21:45:00Z",
      "close": 111.522,
      "ema": {
        "20": 111.55190729942815,
        "50": 111.61249249261753,
        "200": 111.83707962165322
      },
      "ema20_change_5bars": -0.017102731875866084,
      "atr14": 0.05463891145001999,
      "trend": "SELL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-14T22:00:00Z",
      "close": 111.879,
      "ema": {
        "20": 112.71085994095063,
        "50": 112.65552119561359,
        "200": 107.52366130308037
      },
      "ema20_change_5bars": -0.40072215398839717,
      "atr14": 1.6001507378576685,
      "trend": "NEUTRAL"
    }
  },
  "candidates": [
    {
      "symbol": "CADJPY",
      "enabled": 0,
      "direction": "SELL",
      "mode": "BREAKOUT",
      "zone_low": 111.575,
      "zone_high": 111.613,
      "invalidation": 111.645,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.5,
      "factor_group": "JPY_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 0.418,
      "pivot": {
        "side": "LOW",
        "level": 111.594,
        "index": 988,
        "confirmed_index": 990,
        "pivot_utc": "2026-11-16T10:00:00Z",
        "confirmed_utc": "2026-11-16T12:00:00Z"
      },
      "breakout_close_utc": "2026-11-16T18:00:00Z",
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": true,
      "valid_until_utc": "2026-11-17T21:45:00Z"
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
    "broker_symbol": "CADJPY",
    "tick_time_utc": "2026-11-16T21:46:06Z",
    "bid": 111.503,
    "ask": 111.53,
    "digits": 3,
    "point": 0.001,
    "spread_points": 27.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -1e-12
  },
  "rtv": {
    "value": 0.4511742892459827,
    "baseline_median": 809.0,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-16T21:45:00Z"
  }
}
```
