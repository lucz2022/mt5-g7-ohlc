# CADCHF candidate evidence

JSON SHA-256: 5d92155583631cefb000aec399fa26933e2c803a20245312044bb79f3ccc7360

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "CADCHF",
  "as_of_utc": "2026-11-16T12:30:00Z",
  "price_basis": "BID",
  "status": "REJECT",
  "reasons": [
    "D1_H4_TREND_CONFLICT"
  ],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/CADCHF/D1.json",
      "sha256": "74dd734ac5e0bd12fc82d6e71827aed220f68c51a044e5c1d14a93b925d06951",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CADCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T02:50:25Z",
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
      "path": "ohlc/pairs/CADCHF/H4.json",
      "sha256": "cf4d536757eb949e6b34fe5ea6f1329aad6f0a829ec00f312f387ec462dbe5a7",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CADCHF",
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
      "path": "ohlc/pairs/CADCHF/H1.json",
      "sha256": "7967b138e7982843569fbf0894470250eb56b93ad64a4bdd9d744f670971cc11",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CADCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T12:01:13Z",
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
      "path": "ohlc/pairs/CADCHF/M15.json",
      "sha256": "cb84d87177a184ea92e19dbd93b7cb64d7ecdee8d4d27399503238400b177642",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CADCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T12:31:12Z",
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
      "path": "ohlc/pairs/CADCHF/W1.json",
      "sha256": "48d412bc237770d55ab36dccd70ba1494ec0f1158c17863024ce1285fc05c080",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CADCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T02:50:55Z",
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
      "close": 0.58774,
      "ema": {
        "20": 0.5852981941197207,
        "50": 0.58474401346899,
        "200": 0.5803503554433372
      },
      "ema20_change_5bars": -0.0005677202894145417,
      "atr14": 0.003821306276297417,
      "trend": "NEUTRAL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-16T10:00:00Z",
      "close": 0.58829,
      "ema": {
        "20": 0.5859791897856731,
        "50": 0.5850011593414057,
        "200": 0.5853558718423003
      },
      "ema20_change_5bars": 0.0012793985645395134,
      "atr14": 0.0013191456692585037,
      "trend": "BUY"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T12:00:00Z",
      "close": 0.58821,
      "ema": {
        "20": 0.5878164661329194,
        "50": 0.5868377546206186,
        "200": 0.5849918961382269
      },
      "ema20_change_5bars": 0.00018532327073095267,
      "atr14": 0.0006219127196084864,
      "trend": "BUY"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T12:30:00Z",
      "close": 0.58739,
      "ema": {
        "20": 0.5880410166058981,
        "50": 0.5879378293623044,
        "200": 0.5868334854318261
      },
      "ema20_change_5bars": -2.15837187114154e-05,
      "atr14": 0.000309996943860001,
      "trend": "NEUTRAL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-14T22:00:00Z",
      "close": 0.58774,
      "ema": {
        "20": 0.5822238409311021,
        "50": 0.5805730921228468,
        "200": 0.6233603591580497
      },
      "ema20_change_5bars": 0.0024891204976482673,
      "atr14": 0.007554317428246551,
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
    "broker_symbol": "CADCHF",
    "tick_time_utc": "2026-11-16T12:31:08Z",
    "bid": 0.58729,
    "ask": 0.5874,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 11.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -5e-12
  },
  "rtv": {
    "value": 1.6884057971014492,
    "baseline_median": 552.0,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-16T12:30:00Z"
  }
}
```
