# EURAUD candidate evidence

JSON SHA-256: 3c43c6090a36b1bf90e842a6d406f742c21c04888a8b3ba890585459fc331c0d

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "EURAUD",
  "as_of_utc": "2026-11-24T06:15:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/EURAUD/D1.json",
      "sha256": "ae494393136a92823b4a212966eb8015ea5bc2ebe74e43924390669e93477f9b",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURAUD",
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
    },
    "H4": {
      "path": "ohlc/pairs/EURAUD/H4.json",
      "sha256": "70b7333305e35cd4f7a725c3487ec021bb6603fa27d6bec8e9d0afd5a8ff957b",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURAUD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T06:01:13Z",
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
      "path": "ohlc/pairs/EURAUD/H1.json",
      "sha256": "74c3e8f95c94a2208da5811d21adabfe452454e7715c00c515dbde488bfe8648",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURAUD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T06:01:13Z",
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
      "path": "ohlc/pairs/EURAUD/M15.json",
      "sha256": "5f47c03004997deea22adea7e061d95b145d4b825083ea9e8a08bc7965150a88",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURAUD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T06:16:10Z",
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
      "path": "ohlc/pairs/EURAUD/W1.json",
      "sha256": "5d90e2588c4f5ea38f8e8a8d503898d1f85f05ae1be5d40023ede1cec333e6ba",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURAUD",
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
      "last_closed_bar_utc": "2026-11-23T22:00:00Z",
      "close": 1.64472,
      "ema": {
        "20": 1.6255864825951887,
        "50": 1.618901381371968,
        "200": 1.6417462394198723
      },
      "ema20_change_5bars": 0.012018571855960447,
      "atr14": 0.011333198048639415,
      "trend": "BUY"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-24T06:00:00Z",
      "close": 1.6454499999999999,
      "ema": {
        "20": 1.6456453423987096,
        "50": 1.6376465380472773,
        "200": 1.6204336579554703
      },
      "ema20_change_5bars": 8.684205768405562e-05,
      "atr14": 0.005256552087460065,
      "trend": "BUY"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-24T06:00:00Z",
      "close": 1.6454499999999999,
      "ema": {
        "20": 1.6469364849729942,
        "50": 1.6473975132011058,
        "200": 1.637476526267215
      },
      "ema20_change_5bars": -0.0003722108241817068,
      "atr14": 0.0027466987757287353,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-24T06:15:00Z",
      "close": 1.64596,
      "ema": {
        "20": 1.6460261031104395,
        "50": 1.64628573862067,
        "200": 1.647465106607001
      },
      "ema20_change_5bars": -0.00026763850467736994,
      "atr14": 0.0012019661147053618,
      "trend": "SELL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-21T22:00:00Z",
      "close": 1.6565400000000001,
      "ema": {
        "20": 1.6247488759317235,
        "50": 1.6506128853063595,
        "200": 1.652351272763271
      },
      "ema20_change_5bars": -0.00296492727308717,
      "atr14": 0.021842628613531617,
      "trend": "NEUTRAL"
    }
  },
  "candidates": [
    {
      "symbol": "EURAUD",
      "enabled": 0,
      "direction": "BUY",
      "mode": "PULLBACK",
      "zone_low": 1.64244,
      "zone_high": 1.64326,
      "invalidation": 1.64175,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.5,
      "factor_group": "EUR_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 0.983,
      "pivot": {
        "side": "LOW",
        "level": 1.6428500000000001,
        "index": 993,
        "confirmed_index": 995,
        "pivot_utc": "2026-11-24T00:00:00Z",
        "confirmed_utc": "2026-11-24T02:00:00Z"
      },
      "breakout_close_utc": null,
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": false,
      "valid_until_utc": "2026-11-25T06:15:00Z"
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
    "broker_symbol": "EURAUD",
    "tick_time_utc": "2026-11-24T06:16:06Z",
    "bid": 1.64598,
    "ask": 1.6461299999999999,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 15.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": 1.3e-11
  },
  "rtv": {
    "value": 1.0090293453724606,
    "baseline_median": 886.0,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-24T06:15:00Z"
  }
}
```
