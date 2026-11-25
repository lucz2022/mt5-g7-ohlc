# EURGBP candidate evidence

JSON SHA-256: 7277edb2a9ec8fb8208cb4cd434c9d8b9644e1395e08d25f344fffbd47ce6eeb

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "EURGBP",
  "as_of_utc": "2026-11-25T00:45:00Z",
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
      "sha256": "f56fcff8ab376b2f362c2d8cac230ca971731236c473f6c992cf77c4c935e3f5",
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
    "H1": {
      "path": "ohlc/pairs/EURGBP/H1.json",
      "sha256": "ea4984b79c5121b0d4142a480aa4f69a7a3ec102799d9b1ff22d2b70c42e17c3",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURGBP",
      "digits": 5,
      "retrieved_at_utc": "2026-11-25T00:01:10Z",
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
      "sha256": "d638ef72b6b9d591db4c0c552ead51626e7a64ce1a36ddfd58bbe7a699048072",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURGBP",
      "digits": 5,
      "retrieved_at_utc": "2026-11-25T00:46:08Z",
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
      "last_closed_bar_utc": "2026-11-24T22:00:00Z",
      "close": 0.836,
      "ema": {
        "20": 0.8365319741184211,
        "50": 0.8359593445444286,
        "200": 0.8389916704124515
      },
      "ema20_change_5bars": -1.8211536117473948e-05,
      "atr14": 0.0011470754696111156,
      "trend": "NEUTRAL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-25T00:00:00Z",
      "close": 0.83605,
      "ema": {
        "20": 0.8363983479999769,
        "50": 0.83661215584155,
        "200": 0.8359400065305579
      },
      "ema20_change_5bars": -0.0002283883482281368,
      "atr14": 0.0005385518446486834,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-25T00:45:00Z",
      "close": 0.83619,
      "ema": {
        "20": 0.8360946749182494,
        "50": 0.8362687882104181,
        "200": 0.8366100184784566
      },
      "ema20_change_5bars": -8.860565710588908e-06,
      "atr14": 0.0002563672415697982,
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
    "tick_time_utc": "2026-11-25T00:46:05Z",
    "bid": 0.8361,
    "ask": 0.8362,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 10.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -1e-11
  },
  "rtv": {
    "value": 2.8274706867671693,
    "baseline_median": 298.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-25T00:45:00Z"
  }
}
```
