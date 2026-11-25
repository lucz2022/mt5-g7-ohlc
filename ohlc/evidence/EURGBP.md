# EURGBP candidate evidence

JSON SHA-256: e0f40097f5be186d4837788a0dc5b835edb1e81f6f42ea747bf775e78e48cb55

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "EURGBP",
  "as_of_utc": "2026-11-25T04:30:00Z",
  "price_basis": "BID",
  "status": "REJECT",
  "reasons": [
    "D1_H4_TREND_CONFLICT"
  ],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/EURGBP/D1.json",
      "sha256": "8f57e0f189f30af5250cb8a2995a8766c1c26aeb4cea9b3142fbd7a93dafb367",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURGBP",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T22:01:30Z",
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
      "path": "ohlc/pairs/EURGBP/H4.json",
      "sha256": "8b8491a5948cb0ac752752379bbc913dab6a23c9c8063a85aacfed332ffa3a9e",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURGBP",
      "digits": 5,
      "retrieved_at_utc": "2026-11-25T02:01:09Z",
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
      "path": "ohlc/pairs/EURGBP/H1.json",
      "sha256": "12f53d213d5236eeb16661b237c648353ea21678d8526f24d7cf7d8e09f8718e",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURGBP",
      "digits": 5,
      "retrieved_at_utc": "2026-11-25T04:01:10Z",
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
      "path": "ohlc/pairs/EURGBP/M15.json",
      "sha256": "eb7c0164c648d2bc3a9b3b4f39dca47159ecbf7520f5b2e3b320062d31c70001",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURGBP",
      "digits": 5,
      "retrieved_at_utc": "2026-11-25T04:31:09Z",
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
      "path": "ohlc/pairs/EURGBP/W1.json",
      "sha256": "63d49e833f467064acfaea9fe0d51c800e28299c5c1a3264c89ee22768952a09",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURGBP",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T03:31:09Z",
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
      "close": 0.836,
      "ema": {
        "20": 0.836556435124622,
        "50": 0.8417078457277394,
        "200": 0.853725282180438
      },
      "ema20_change_5bars": 3.228657123066636e-05,
      "atr14": 0.0027081963240628546,
      "trend": "NEUTRAL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-25T02:00:00Z",
      "close": 0.83606,
      "ema": {
        "20": 0.836487024202381,
        "50": 0.8359632918177823,
        "200": 0.8389627035110702
      },
      "ema20_change_5bars": -5.5524723153954625e-05,
      "atr14": 0.0011301415074960336,
      "trend": "NEUTRAL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-25T04:00:00Z",
      "close": 0.83608,
      "ema": {
        "20": 0.8362756975216346,
        "50": 0.8365247690390166,
        "200": 0.8359430685003724
      },
      "ema20_change_5bars": -0.00015931868886631673,
      "atr14": 0.0004887702841266861,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-25T04:30:00Z",
      "close": 0.83597,
      "ema": {
        "20": 0.8360688232996384,
        "50": 0.8361708634272105,
        "200": 0.8365312711738314
      },
      "ema20_change_5bars": -3.0022965420428704e-06,
      "atr14": 0.000213450891722602,
      "trend": "SELL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-21T22:00:00Z",
      "close": 0.83798,
      "ema": {
        "20": 0.8477818470727907,
        "50": 0.8553561223292049,
        "200": 0.8575653202335151
      },
      "ema20_change_5bars": -0.00800371057729976,
      "atr14": 0.006063962308599809,
      "trend": "SELL"
    }
  },
  "candidates": [],
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
    "broker_symbol": "EURGBP",
    "tick_time_utc": "2026-11-25T04:31:07Z",
    "bid": 0.83592,
    "ask": 0.83603,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 11.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -5e-12
  },
  "rtv": {
    "value": 0.5582870737509913,
    "baseline_median": 630.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-25T04:30:00Z"
  }
}
```
