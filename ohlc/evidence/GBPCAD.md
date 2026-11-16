# GBPCAD candidate evidence

JSON SHA-256: c749799f3718f414ceb3057508ebb35151eb9ce803d06716c468621e5f9c072a

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "GBPCAD",
  "as_of_utc": "2026-11-16T09:00:00Z",
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
      "sha256": "7a42f3206d4fe248034dcc3b5e5460b9cdc38075238429f492776259a0205dcc",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPCAD",
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
      "path": "ohlc/pairs/GBPCAD/H1.json",
      "sha256": "05a028797904064630bb4946846cf0050bb1bb5499e8e6ef93188f480ed29885",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T09:01:15Z",
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
      "sha256": "4b992288873ab05cb94ad6e9fbe4e26c1458cdadd058c75dc0fdd67dbd3d2234",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T09:01:15Z",
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
      "last_closed_bar_utc": "2026-11-16T06:00:00Z",
      "close": 1.88527,
      "ema": {
        "20": 1.8877729251230733,
        "50": 1.88655377271541,
        "200": 1.8812882365948063
      },
      "ema20_change_5bars": -0.001723030583087315,
      "atr14": 0.0028270485981523,
      "trend": "NEUTRAL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T09:00:00Z",
      "close": 1.8869,
      "ema": {
        "20": 1.8855536559028245,
        "50": 1.8867741202310981,
        "200": 1.8864465996089856
      },
      "ema20_change_5bars": -1.8687483438029062e-05,
      "atr14": 0.001315732679683329,
      "trend": "NEUTRAL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T09:00:00Z",
      "close": 1.8869,
      "ema": {
        "20": 1.885600597647061,
        "50": 1.8854932053359117,
        "200": 1.8868304057807297
      },
      "ema20_change_5bars": 0.0002763808564723025,
      "atr14": 0.000731140881930735,
      "trend": "BUY"
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
    "tick_time_utc": "2026-11-16T09:01:10Z",
    "bid": 1.88727,
    "ask": 1.88742,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 15.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -9e-12
  },
  "rtv": {
    "value": 1.2806092560046867,
    "baseline_median": 853.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-16T09:00:00Z"
  }
}
```
