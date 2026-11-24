# USDCHF candidate evidence

JSON SHA-256: 9ca0077218641353109a8281e441f459f7730f7817ca6af61fa4825c666e32d5

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "USDCHF",
  "as_of_utc": "2026-11-24T13:30:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/USDCHF/D1.json",
      "sha256": "9125a645b73b2b5eee3939355e7946b4650394a6c8db3201af25fe38698bde8b",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T03:31:08Z",
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
      "path": "ohlc/pairs/USDCHF/H4.json",
      "sha256": "a71f205a25329d01b5162bf650b117a551ea5b7a112e85af4d870d8dde8d35d3",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T10:01:10Z",
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
      "path": "ohlc/pairs/USDCHF/H1.json",
      "sha256": "21c784f305f1508a641f34e64aeb5627fdcd93d0ca1c1e054b55c1bda1635bfa",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T13:01:09Z",
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
      "path": "ohlc/pairs/USDCHF/M15.json",
      "sha256": "43248639a7af39963591a406bcfdea2a55e62082bfd34b307aa79f8534f0ff2f",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T13:31:17Z",
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
      "path": "ohlc/pairs/USDCHF/W1.json",
      "sha256": "e12621a0212e260154a5299dd3e44d3d6edf4cf9d39668f46ade4507787a003b",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T03:31:08Z",
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
      "last_closed_bar_utc": "2026-11-23T22:00:00Z",
      "close": 0.84136,
      "ema": {
        "20": 0.833361861983558,
        "50": 0.827353318809423,
        "200": 0.8131068541637182
      },
      "ema20_change_5bars": 0.005510626152958609,
      "atr14": 0.005632268672628738,
      "trend": "BUY"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-24T10:00:00Z",
      "close": 0.84093,
      "ema": {
        "20": 0.8410425177043641,
        "50": 0.8383352693384251,
        "200": 0.8300407399630102
      },
      "ema20_change_5bars": 0.00031390287962917984,
      "atr14": 0.0022389654563929216,
      "trend": "BUY"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-24T13:00:00Z",
      "close": 0.83841,
      "ema": {
        "20": 0.8407957360123293,
        "50": 0.8409845694431821,
        "200": 0.8383611117629151
      },
      "ema20_change_5bars": -0.0006271168637834723,
      "atr14": 0.0011775691571023809,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 250,
      "last_closed_bar_utc": "2026-11-24T13:30:00Z",
      "close": 0.8374,
      "ema": {
        "20": 0.8393541335661358,
        "50": 0.8404323182172624,
        "200": 0.8408229561900403
      },
      "ema20_change_5bars": -0.0010908505526692203,
      "atr14": 0.0007592921598443533,
      "trend": "SELL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-21T22:00:00Z",
      "close": 0.84025,
      "ema": {
        "20": 0.8198741974031807,
        "50": 0.8116401539498772,
        "200": 0.849359997999963
      },
      "ema20_change_5bars": 0.0071074832982408465,
      "atr14": 0.012303220480855583,
      "trend": "BUY"
    }
  },
  "candidates": [
    {
      "symbol": "USDCHF",
      "enabled": 0,
      "direction": "BUY",
      "mode": "PULLBACK",
      "zone_low": 0.8365,
      "zone_high": 0.83686,
      "invalidation": 0.83621,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.75,
      "factor_group": "USD_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 0.4586,
      "pivot": {
        "side": "LOW",
        "level": 0.83668,
        "index": 971,
        "confirmed_index": 973,
        "pivot_utc": "2026-11-23T09:00:00Z",
        "confirmed_utc": "2026-11-23T11:00:00Z"
      },
      "breakout_close_utc": null,
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": false,
      "valid_until_utc": "2026-11-25T13:30:00Z"
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
    "broker_symbol": "USDCHF",
    "tick_time_utc": "2026-11-24T13:31:16Z",
    "bid": 0.83745,
    "ask": 0.83754,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 9.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": 8e-12
  },
  "rtv": {
    "value": 1.7784172661870503,
    "baseline_median": 695.0,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-24T13:30:00Z"
  }
}
```
