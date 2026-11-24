# AUDCHF candidate evidence

JSON SHA-256: cfd13d66ec333c401afdffc39588f43af73ee1cc6a4b3356491c7633e48f60dd

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "AUDCHF",
  "as_of_utc": "2026-11-24T11:15:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/AUDCHF/D1.json",
      "sha256": "fecb6a11e34ff3f7ad3259dd53cc9c57b9a38b29f308573a19b1457d1f9f0c2b",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T03:31:11Z",
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
      "path": "ohlc/pairs/AUDCHF/H4.json",
      "sha256": "4fcd06b491ba3aba2f62ebbfdcdf5d737542659f46def984e4925a1d47b4fde4",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T10:01:16Z",
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
      "path": "ohlc/pairs/AUDCHF/H1.json",
      "sha256": "5fda5a315f9df2148501e23be83805948250e2eef9500b29faadb217d237485d",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T11:01:12Z",
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
      "path": "ohlc/pairs/AUDCHF/M15.json",
      "sha256": "7915d1bf9d44d4a0f7f214e1db63c0def99d43c67d3fa0e7dafcffe5ea1ae357",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T11:16:12Z",
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
      "path": "ohlc/pairs/AUDCHF/W1.json",
      "sha256": "108a2191b6e9a84a59742c954a28f2fe2bdf7d85538ce48d63275de52c664f44",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T03:31:11Z",
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
      "close": 0.55764,
      "ema": {
        "20": 0.5676212092485531,
        "50": 0.5723628482368374,
        "200": 0.5653323792595971
      },
      "ema20_change_5bars": -0.0043237336205425025,
      "atr14": 0.005169044178924302,
      "trend": "SELL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-24T10:00:00Z",
      "close": 0.55735,
      "ema": {
        "20": 0.559596241835851,
        "50": 0.5629463028971833,
        "200": 0.5706598660435717
      },
      "ema20_change_5bars": -0.0012582652812072048,
      "atr14": 0.0023889725358399476,
      "trend": "SELL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-24T11:00:00Z",
      "close": 0.55648,
      "ema": {
        "20": 0.5576701353477043,
        "50": 0.5584857293255531,
        "200": 0.5629959782689373
      },
      "ema20_change_5bars": -6.391693521923258e-05,
      "atr14": 0.001229999528690446,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-24T11:15:00Z",
      "close": 0.55598,
      "ema": {
        "20": 0.5575104887914986,
        "50": 0.5576933401410825,
        "200": 0.558499752683035
      },
      "ema20_change_5bars": -0.0004466531417794961,
      "atr14": 0.0006274155585463732,
      "trend": "SELL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-21T22:00:00Z",
      "close": 0.55591,
      "ema": {
        "20": 0.5706053552543319,
        "50": 0.5620488215813056,
        "200": 0.5796629162759163
      },
      "ema20_change_5bars": -0.0015468899505538536,
      "atr14": 0.009907778232017057,
      "trend": "NEUTRAL"
    }
  },
  "candidates": [
    {
      "symbol": "AUDCHF",
      "enabled": 0,
      "direction": "SELL",
      "mode": "BREAKOUT",
      "zone_low": 0.55656,
      "zone_high": 0.55692,
      "invalidation": 0.55723,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.5,
      "factor_group": "CHF_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 0.4715,
      "pivot": {
        "side": "LOW",
        "level": 0.55674,
        "index": 992,
        "confirmed_index": 994,
        "pivot_utc": "2026-11-24T04:00:00Z",
        "confirmed_utc": "2026-11-24T06:00:00Z"
      },
      "breakout_close_utc": "2026-11-24T11:00:00Z",
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": true,
      "valid_until_utc": "2026-11-25T11:15:00Z"
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
    "broker_symbol": "AUDCHF",
    "tick_time_utc": "2026-11-24T11:16:07Z",
    "bid": 0.55588,
    "ask": 0.556,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 12.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -1e-12
  },
  "rtv": {
    "value": 0.936016511867905,
    "baseline_median": 969.0,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-24T11:15:00Z"
  }
}
```
