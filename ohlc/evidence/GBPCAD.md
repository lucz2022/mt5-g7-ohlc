# GBPCAD candidate evidence

JSON SHA-256: b54e6dcbb8f8e18bbbd0d872a3ce5f45692ae66a2b1617c6ff16fc0a874cdba9

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "GBPCAD",
  "as_of_utc": "2026-11-16T13:00:00Z",
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
      "sha256": "b73ccfb0b95e5bd30917a4835e7421bf54ecbc1c2b09d1c37f01073d4f4641f7",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T10:01:11Z",
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
      "sha256": "d5a271ba2d59d0e6510f24db092feaca12d56ac1a7bdfc67c6bb244d58d1aa41",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T13:01:14Z",
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
      "sha256": "9093ceecbcd62bd507b245a16f06dfbf5eeba74cacc38d6d433fdf5f045aa500",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T13:01:14Z",
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
      "last_closed_bar_utc": "2026-11-16T10:00:00Z",
      "close": 1.88407,
      "ema": {
        "20": 1.8874202655875425,
        "50": 1.8864563698587253,
        "200": 1.881316455414399
      },
      "ema20_change_5bars": -0.0016617895751742662,
      "atr14": 0.0029122594125699864,
      "trend": "NEUTRAL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T13:00:00Z",
      "close": 1.88585,
      "ema": {
        "20": 1.8852787696017195,
        "50": 1.886462804265883,
        "200": 1.8863759037351298
      },
      "ema20_change_5bars": -0.00013316586982337064,
      "atr14": 0.0015509590031350157,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T13:00:00Z",
      "close": 1.88585,
      "ema": {
        "20": 1.884944987605708,
        "50": 1.8851349249062088,
        "200": 1.886519925744128
      },
      "ema20_change_5bars": 0.00022315715165155403,
      "atr14": 0.0008457527446007406,
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
    "tick_time_utc": "2026-11-16T13:01:10Z",
    "bid": 1.8858000000000001,
    "ask": 1.88592,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 12.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": 1e-11
  },
  "rtv": {
    "value": 1.1860885275519422,
    "baseline_median": 1107.0,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-16T13:00:00Z"
  }
}
```
