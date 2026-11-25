# EURCHF candidate evidence

JSON SHA-256: 50e989a6ac464f1894ceb283e5812a660a0943c5d97d0e414869107299ccaabc

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "EURCHF",
  "as_of_utc": "2026-11-25T02:45:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/EURCHF/D1.json",
      "sha256": "b554d0f60a26440185d3f028c5ad43c383f433516915cabc170546775561e9b7",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T22:01:31Z",
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
      "path": "ohlc/pairs/EURCHF/H4.json",
      "sha256": "f632ad2908b202bf383b911f0dd79509e79d732f8d45dee3ba3f8e30ac38d5c8",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-25T02:01:10Z",
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
      "path": "ohlc/pairs/EURCHF/H1.json",
      "sha256": "60a7fb85e2d843334064d6216db532244c1caf3c13fb5dda335b2a2a9f3708e3",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURCHF",
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
    "M15": {
      "path": "ohlc/pairs/EURCHF/M15.json",
      "sha256": "6f8294ef2550f7dac347a4ec949660b82af401fff63f09df4e7488d0c5509a5b",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-25T02:46:11Z",
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
      "path": "ohlc/pairs/EURCHF/W1.json",
      "sha256": "08610e30ba1ce9e6c33f792d8ed282c797a8552f908ed6b374f8b22fb2fc5ae1",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T03:31:10Z",
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
      "close": 0.91618,
      "ema": {
        "20": 0.9221437057446793,
        "50": 0.9262364771685629,
        "200": 0.9275125312302754
      },
      "ema20_change_5bars": -0.000982532832837446,
      "atr14": 0.005331489454909198,
      "trend": "SELL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-25T02:00:00Z",
      "close": 0.916,
      "ema": {
        "20": 0.9196716642377638,
        "50": 0.9213503807319555,
        "200": 0.9244728676067827
      },
      "ema20_change_5bars": -0.001641428689907909,
      "atr14": 0.0022461745924467046,
      "trend": "SELL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-25T02:00:00Z",
      "close": 0.916,
      "ema": {
        "20": 0.9169423940021963,
        "50": 0.9185357096204771,
        "200": 0.9213891303883726
      },
      "ema20_change_5bars": -0.0005701863214353509,
      "atr14": 0.0009519755917618902,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-25T02:45:00Z",
      "close": 0.91577,
      "ema": {
        "20": 0.9160570918281435,
        "50": 0.9164242039709266,
        "200": 0.9184453675895784
      },
      "ema20_change_5bars": -5.435643479478891e-05,
      "atr14": 0.00037910210705187304,
      "trend": "SELL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-21T22:00:00Z",
      "close": 0.92136,
      "ema": {
        "20": 0.9273195931591544,
        "50": 0.9273090492819839,
        "200": 0.9547811560766248
      },
      "ema20_change_5bars": -0.004174569610950973,
      "atr14": 0.009882127679685394,
      "trend": "NEUTRAL"
    }
  },
  "candidates": [
    {
      "symbol": "EURCHF",
      "enabled": 0,
      "direction": "SELL",
      "mode": "BREAKOUT",
      "zone_low": 0.91758,
      "zone_high": 0.91786,
      "invalidation": 0.9181,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.5,
      "factor_group": "CHF_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 1.9013,
      "pivot": {
        "side": "LOW",
        "level": 0.91772,
        "index": 980,
        "confirmed_index": 982,
        "pivot_utc": "2026-11-24T07:00:00Z",
        "confirmed_utc": "2026-11-24T09:00:00Z"
      },
      "breakout_close_utc": "2026-11-24T15:00:00Z",
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": true,
      "valid_until_utc": "2026-11-26T02:45:00Z"
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
    "broker_symbol": "EURCHF",
    "tick_time_utc": "2026-11-25T02:46:09Z",
    "bid": 0.91575,
    "ask": 0.91589,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 14.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -3e-12
  },
  "rtv": {
    "value": 1.3106960950764006,
    "baseline_median": 589.0,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-25T02:45:00Z"
  }
}
```
