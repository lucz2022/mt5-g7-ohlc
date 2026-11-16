# GBPCAD candidate evidence

JSON SHA-256: e94b64bc11bc6dd7df0e98d2efe273126d5038fa60c661cf8d2f4d0023758984

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "GBPCAD",
  "as_of_utc": "2026-11-16T18:30:00Z",
  "price_basis": "BID",
  "status": "REJECT",
  "reasons": [
    "D1_H4_TREND_CONFLICT"
  ],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/GBPCAD/D1.json",
      "sha256": "02720af1151e04eb290c8a3f4870652c3f3e6ed1eeb2abd380f65f3a8cf65432",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T02:48:31Z",
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
      "path": "ohlc/pairs/GBPCAD/H4.json",
      "sha256": "bf5d8506a3f8e49b18faedf74ef97eec14ddf505e6a9446c28324daa12c6c7dc",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T18:01:11Z",
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
      "path": "ohlc/pairs/GBPCAD/H1.json",
      "sha256": "3046d0eeb9da7b799b1496b35d520edb6ee72ed2717eb4a619bae279acfbdf5b",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T18:01:11Z",
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
      "path": "ohlc/pairs/GBPCAD/M15.json",
      "sha256": "be920244d2f553a0c8d7eb7ae432a3b922a66ebe6f66775faefe1e596fa1e422",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T18:31:13Z",
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
      "path": "ohlc/pairs/GBPCAD/W1.json",
      "sha256": "9f0b1addc37110fbe38a8914f0ce7b3734bbf8a22e513cba501bbb13d5d095c0",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T02:49:09Z",
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
      "close": 1.88487,
      "ema": {
        "20": 1.8829298180309062,
        "50": 1.8801985712280664,
        "200": 1.8698494728479982
      },
      "ema20_change_5bars": 0.004721674693405342,
      "atr14": 0.008212664904972855,
      "trend": "BUY"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-16T18:00:00Z",
      "close": 1.88586,
      "ema": {
        "20": 1.8872389022156528,
        "50": 1.8864549727065512,
        "200": 1.8814203290651523
      },
      "ema20_change_5bars": -0.001002371965165283,
      "atr14": 0.003004601228185352,
      "trend": "NEUTRAL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T18:00:00Z",
      "close": 1.88586,
      "ema": {
        "20": 1.8856276501369695,
        "50": 1.8864136348700566,
        "200": 1.886367571949828
      },
      "ema20_change_5bars": 0.00034888053525006235,
      "atr14": 0.0016245489623947817,
      "trend": "NEUTRAL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T18:30:00Z",
      "close": 1.88524,
      "ema": {
        "20": 1.885902598459744,
        "50": 1.8857391268022954,
        "200": 1.8864634019267472
      },
      "ema20_change_5bars": -0.0002641984300570943,
      "atr14": 0.0008486792273851084,
      "trend": "NEUTRAL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-14T22:00:00Z",
      "close": 1.88487,
      "ema": {
        "20": 1.876952800291378,
        "50": 1.8657930830978018,
        "200": 1.794037200320413
      },
      "ema20_change_5bars": 0.0020901440717289166,
      "atr14": 0.017441474279700712,
      "trend": "BUY"
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
    "broker_symbol": "GBPCAD",
    "tick_time_utc": "2026-11-16T18:31:09Z",
    "bid": 1.8852799999999998,
    "ask": 1.88541,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 13.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -1.9e-11
  },
  "rtv": {
    "value": 0.73822851498189,
    "baseline_median": 1518.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-16T18:30:00Z"
  }
}
```
