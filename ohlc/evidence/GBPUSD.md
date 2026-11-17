# GBPUSD candidate evidence

JSON SHA-256: 441910ff5bb7fbb487a10afd334869c2ae950abea4f9a7e26509ac8d1f5b7906

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "GBPUSD",
  "as_of_utc": "2026-11-17T00:15:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/GBPUSD/D1.json",
      "sha256": "f04bd585414c9f8e072d784e559d229f68a6c91d1e14ab500ad2b51e1ad28e1b",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T22:01:12Z",
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
      "path": "ohlc/pairs/GBPUSD/H4.json",
      "sha256": "6f3f2ce382313669a50d2ea06b7d54d24abe9d8b7fb5390f89872f51103257be",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T22:01:12Z",
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
      "path": "ohlc/pairs/GBPUSD/H1.json",
      "sha256": "8fad842934a592880eea9898ea18b59ace7ecb777d16185d2996419232895d6f",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-17T00:01:09Z",
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
      "path": "ohlc/pairs/GBPUSD/M15.json",
      "sha256": "d014d8bb4d813edbf33c6271d441c35dfb4060328cc2d9bc315e299361189c88",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-17T00:16:08Z",
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
      "path": "ohlc/pairs/GBPUSD/W1.json",
      "sha256": "75e24fe51244c56882a978d22ef62ca684220a36bd84dcb455be6f20d14cd65c",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T02:32:59Z",
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
      "close": 1.31849,
      "ema": {
        "20": 1.332081099360926,
        "50": 1.3346542982897804,
        "200": 1.3377719439494329
      },
      "ema20_change_5bars": -0.005069233731998635,
      "atr14": 0.007391086050169612,
      "trend": "SELL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-16T22:00:00Z",
      "close": 1.31849,
      "ema": {
        "20": 1.3237746870838687,
        "50": 1.3299833685760918,
        "200": 1.3339521781041377
      },
      "ema20_change_5bars": -0.002874073007676614,
      "atr14": 0.002522644996471481,
      "trend": "SELL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-17T00:00:00Z",
      "close": 1.31841,
      "ema": {
        "20": 1.3192815264002091,
        "50": 1.3213409871081647,
        "200": 1.329879552605852
      },
      "ema20_change_5bars": -0.0005662251447091649,
      "atr14": 0.001187339546926663,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-17T00:15:00Z",
      "close": 1.31846,
      "ema": {
        "20": 1.3185270174892896,
        "50": 1.318921881921093,
        "200": 1.321407289297474
      },
      "ema20_change_5bars": -4.513457531851728e-05,
      "atr14": 0.0004312473441848889,
      "trend": "SELL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-14T22:00:00Z",
      "close": 1.32116,
      "ema": {
        "20": 1.336832598663811,
        "50": 1.3371038844414553,
        "200": 1.3134424165483185
      },
      "ema20_change_5bars": -0.0028835352773075584,
      "atr14": 0.016802691861221172,
      "trend": "SELL"
    }
  },
  "candidates": [
    {
      "symbol": "GBPUSD",
      "enabled": 0,
      "direction": "SELL",
      "mode": "BREAKOUT",
      "zone_low": 1.32034,
      "zone_high": 1.3207,
      "invalidation": 1.321,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.75,
      "factor_group": "USD_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 1.5834,
      "pivot": {
        "side": "LOW",
        "level": 1.3205200000000001,
        "index": 969,
        "confirmed_index": 971,
        "pivot_utc": "2026-11-13T18:00:00Z",
        "confirmed_utc": "2026-11-13T20:00:00Z"
      },
      "breakout_close_utc": "2026-11-16T10:00:00Z",
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": true,
      "valid_until_utc": "2026-11-18T00:15:00Z"
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
    "broker_symbol": "GBPUSD",
    "tick_time_utc": "2026-11-17T00:16:07Z",
    "bid": 1.31825,
    "ask": 1.3183500000000001,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 10.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -2.1e-11
  },
  "rtv": {
    "value": 2.8919860627177703,
    "baseline_median": 287.0,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-17T00:15:00Z"
  }
}
```
