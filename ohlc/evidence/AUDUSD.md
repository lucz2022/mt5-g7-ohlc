# AUDUSD candidate evidence

JSON SHA-256: 2b4fc7838d210196503d7e10cecebfd1f166a2bb5c67ec8e506dd018ffdea748

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "AUDUSD",
  "as_of_utc": "2026-11-16T21:15:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/AUDUSD/D1.json",
      "sha256": "c6d7e938fb1b01715ce648c6d79141ce149fb46e12b8040ca31080fbcec1a873",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDUSD",
      "digits": 5,
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
      "path": "ohlc/pairs/AUDUSD/H4.json",
      "sha256": "f0f1d677f95bae8b91b993f62b47e7eca5da6bfab93cc76b9eae828c7271d6d5",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T18:01:09Z",
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
      "path": "ohlc/pairs/AUDUSD/H1.json",
      "sha256": "e648bc1d498fa4cc9cff6617d19c3266c699124a78333ddb0903d8cc2ded6960",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T21:01:09Z",
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
      "path": "ohlc/pairs/AUDUSD/M15.json",
      "sha256": "e20af2d9368b94ca2c480d3fdbe098a1a2f58b86e12b857fa36aac5f1e969a78",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T21:16:08Z",
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
      "path": "ohlc/pairs/AUDUSD/W1.json",
      "sha256": "25c2a0c8870e04b454e6ce7a4a1c8690f066cf44b1f36ee497683c1b2e99101f",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T02:33:12Z",
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
      "close": 0.67708,
      "ema": {
        "20": 0.6927677906663852,
        "50": 0.6985451082731482,
        "200": 0.697277312869544
      },
      "ema20_change_5bars": -0.0059379527907119645,
      "atr14": 0.005426442643360679,
      "trend": "SELL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-16T18:00:00Z",
      "close": 0.67465,
      "ema": {
        "20": 0.6797527022213546,
        "50": 0.6858076793455995,
        "200": 0.6956490534385259
      },
      "ema20_change_5bars": -0.002883470684064915,
      "atr14": 0.0018904696244932588,
      "trend": "SELL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T21:00:00Z",
      "close": 0.67339,
      "ema": {
        "20": 0.6753034306379953,
        "50": 0.6775295211801962,
        "200": 0.6856273942907294
      },
      "ema20_change_5bars": -0.0007779895604972387,
      "atr14": 0.0008940683594101826,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T21:15:00Z",
      "close": 0.67338,
      "ema": {
        "20": 0.6740592836682273,
        "50": 0.6747397484443802,
        "200": 0.6775484013642726
      },
      "ema20_change_5bars": -0.00035067856215631465,
      "atr14": 0.00037835570484998516,
      "trend": "SELL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-14T22:00:00Z",
      "close": 0.67708,
      "ema": {
        "20": 0.6998130798434226,
        "50": 0.6940327483605638,
        "200": 0.6827272344123759
      },
      "ema20_change_5bars": -0.005248907040624307,
      "atr14": 0.011269457735274473,
      "trend": "NEUTRAL"
    }
  },
  "candidates": [
    {
      "symbol": "AUDUSD",
      "enabled": 0,
      "direction": "SELL",
      "mode": "BREAKOUT",
      "zone_low": 0.67405,
      "zone_high": 0.67431,
      "invalidation": 0.67453,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.75,
      "factor_group": "USD_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 0.7494,
      "pivot": {
        "side": "LOW",
        "level": 0.67418,
        "index": 994,
        "confirmed_index": 996,
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
      "valid_until_utc": "2026-11-17T21:15:00Z"
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
    "broker_symbol": "AUDUSD",
    "tick_time_utc": "2026-11-16T21:16:00Z",
    "bid": 0.67337,
    "ask": 0.67345,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 8.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": 3e-12
  },
  "rtv": {
    "value": 0.5005005005005005,
    "baseline_median": 499.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-16T21:15:00Z"
  }
}
```
