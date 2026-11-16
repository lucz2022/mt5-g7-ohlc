# AUDUSD candidate evidence

JSON SHA-256: 71a7d94427edf8c736d1bf5d7760b5546053821669bb3d98d9dbea39ca28d457

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "AUDUSD",
  "as_of_utc": "2026-11-16T05:45:00Z",
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
      "sha256": "bf8000d3f76318095d61350ecd2f7a315511c69968e2c65fef2373abb826a2b1",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T02:33:08Z",
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
      "sha256": "e977b1732c3cc5f40425ae195b3213c813b722885216a1526e8dfe318728e4eb",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T05:01:13Z",
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
      "sha256": "4ec8a97e805004702bdacc9dd04b512d5674e9d6f6f2107037794eda75db0bb8",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T05:46:09Z",
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
      "last_closed_bar_utc": "2026-11-16T02:00:00Z",
      "close": 0.67661,
      "ema": {
        "20": 0.6820622516763319,
        "50": 0.6876692829743153,
        "200": 0.6964929980302484
      },
      "ema20_change_5bars": -0.0027183035896565233,
      "atr14": 0.0020316162282319554,
      "trend": "SELL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T05:00:00Z",
      "close": 0.67594,
      "ema": {
        "20": 0.6777778391178397,
        "50": 0.679928157389093,
        "200": 0.6874813659092283
      },
      "ema20_change_5bars": -0.0007624860141556278,
      "atr14": 0.0009402550892203596,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T05:45:00Z",
      "close": 0.67578,
      "ema": {
        "20": 0.6764754766588389,
        "50": 0.6771231268257524,
        "200": 0.6798534629584654
      },
      "ema20_change_5bars": -0.0003643554067772614,
      "atr14": 0.00044373080109887277,
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
      "zone_low": 0.67681,
      "zone_high": 0.67709,
      "invalidation": 0.67733,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.75,
      "factor_group": "USD_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 1.0954,
      "pivot": {
        "side": "LOW",
        "level": 0.67695,
        "index": 992,
        "confirmed_index": 994,
        "pivot_utc": "2026-11-13T22:00:00Z",
        "confirmed_utc": "2026-11-16T00:00:00Z"
      },
      "breakout_close_utc": "2026-11-16T02:00:00Z",
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": true,
      "valid_until_utc": "2026-11-17T05:45:00Z"
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
    "tick_time_utc": "2026-11-16T05:46:08Z",
    "bid": 0.6756,
    "ask": 0.67569,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 9.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -3e-12
  },
  "rtv": {
    "value": 1.0638297872340425,
    "baseline_median": 681.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-16T05:45:00Z"
  }
}
```
