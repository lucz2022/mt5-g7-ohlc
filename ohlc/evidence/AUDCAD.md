# AUDCAD candidate evidence

JSON SHA-256: ed3f71379a441cd9b4399f15f608ea4cd5668dce9d54c9c4dc2c3707c2b8c498

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "AUDCAD",
  "as_of_utc": "2026-11-16T23:30:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/AUDCAD/D1.json",
      "sha256": "afc810e857e49fc1259210dedb4d72815305c2a269a25e4d841782be6a63da96",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T22:01:51Z",
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
      "sha256": "289b0dc26341e2c431eab1bd8822e809f16d73e2c1e450b553b351b245f75a52",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T22:01:51Z",
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
      "sha256": "59edc6a474ebcaffc65991f0ca7f36567a4b5f6202eeeb2f7cf2c2b5767241cd",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T23:01:14Z",
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
      "sha256": "d31a09fb6e3d56a64fd9f453e0ab9aec8e427bae57d7712f8fc85c3f958dc847",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T23:31:12Z",
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
      "last_closed_bar_utc": "2026-11-16T22:00:00Z",
      "close": 0.96328,
      "ema": {
        "20": 0.9767349944585093,
        "50": 0.9827528026118955,
        "200": 0.9743384117305255
      },
      "ema20_change_5bars": -0.0048255047311405175,
      "atr14": 0.006283040545318429,
      "trend": "SELL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-16T22:00:00Z",
      "close": 0.96328,
      "ema": {
        "20": 0.9681574263616549,
        "50": 0.9720082848199021,
        "200": 0.9808126840059797
      },
      "ema20_change_5bars": -0.0025189865608739037,
      "atr14": 0.002312768144022733,
      "trend": "SELL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T23:00:00Z",
      "close": 0.9627,
      "ema": {
        "20": 0.9645379290759205,
        "50": 0.9666109881159489,
        "200": 0.9720247956877677
      },
      "ema20_change_5bars": -0.0008976261167013,
      "atr14": 0.0011104246730456724,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T23:30:00Z",
      "close": 0.96273,
      "ema": {
        "20": 0.9632117399367875,
        "50": 0.9639145482924958,
        "200": 0.9665717686347022
      },
      "ema20_change_5bars": -0.000241313235793017,
      "atr14": 0.0004941239801476147,
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
      "zone_low": 0.96393,
      "zone_high": 0.96427,
      "invalidation": 0.96455,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.5,
      "factor_group": "CAD_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 1.0807,
      "pivot": {
        "side": "LOW",
        "level": 0.9641,
        "index": 992,
        "confirmed_index": 994,
        "pivot_utc": "2026-11-16T16:00:00Z",
        "confirmed_utc": "2026-11-16T18:00:00Z"
      },
      "breakout_close_utc": "2026-11-16T19:00:00Z",
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": true,
      "valid_until_utc": "2026-11-17T23:30:00Z"
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
    "tick_time_utc": "2026-11-16T23:31:06Z",
    "bid": 0.9626,
    "ask": 0.96274,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 14.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -3e-12
  },
  "rtv": {
    "value": 0.46568627450980393,
    "baseline_median": 612.0,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-16T23:30:00Z"
  }
}
```
