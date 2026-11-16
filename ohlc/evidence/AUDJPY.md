# AUDJPY candidate evidence

JSON SHA-256: efb07dac1356c9ccfdf6138b769241c2140c6969bcb57c63d10d52cfe05427d4

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "AUDJPY",
  "as_of_utc": "2026-11-16T17:45:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/AUDJPY/D1.json",
      "sha256": "9e8800230d50e1eaef91031b7b665bfe1ec23da89c7bb655d31f404ed846c248",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDJPY",
      "digits": 3,
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
      "path": "ohlc/pairs/AUDJPY/H4.json",
      "sha256": "1cd25eb73fbc077a64fb231d8527f34001bb3a5b776f5e969bc0a7ae651e2fa9",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T14:01:11Z",
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
      "path": "ohlc/pairs/AUDJPY/H1.json",
      "sha256": "e0ed48f4fa5d9b2ec1367088df49b595e1b0ac20a877b260bae3e5db4c8cd5a8",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T17:01:11Z",
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
      "path": "ohlc/pairs/AUDJPY/M15.json",
      "sha256": "df75dd3eb757a2bf51770f1a1b6b5a7d442a1c4a8adf8dc9f2a96050bb592454",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T17:46:09Z",
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
      "path": "ohlc/pairs/AUDJPY/W1.json",
      "sha256": "ed60b50730b4bca10923c9088f75bf6d54535be59d38cef0c7e7d7724a76f8ea",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T02:33:50Z",
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
      "close": 108.106,
      "ema": {
        "20": 109.77058366943058,
        "50": 110.50869110133104,
        "200": 110.10590981790173
      },
      "ema20_change_5bars": -0.5746653068442384,
      "atr14": 0.9586381385397111,
      "trend": "SELL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-16T14:00:00Z",
      "close": 107.758,
      "ema": {
        "20": 108.523052222492,
        "50": 109.11516325845508,
        "200": 110.10795959972387
      },
      "ema20_change_5bars": -0.43473517006856355,
      "atr14": 0.3707832076056681,
      "trend": "SELL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T17:00:00Z",
      "close": 107.731,
      "ema": {
        "20": 107.90178615475544,
        "50": 108.26240684900657,
        "200": 109.09450518865246
      },
      "ema20_change_5bars": -0.12114942270848417,
      "atr14": 0.18393331630700696,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T17:45:00Z",
      "close": 107.672,
      "ema": {
        "20": 107.71222445046955,
        "50": 107.78842479575393,
        "200": 108.25141461764746
      },
      "ema20_change_5bars": -0.00014555589416431758,
      "atr14": 0.08390759726352195,
      "trend": "SELL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-14T22:00:00Z",
      "close": 108.106,
      "ema": {
        "20": 110.75874224221987,
        "50": 109.18192242632672,
        "200": 100.31143286215332
      },
      "ema20_change_5bars": -0.8643746574648361,
      "atr14": 2.078804028817713,
      "trend": "NEUTRAL"
    }
  },
  "candidates": [
    {
      "symbol": "AUDJPY",
      "enabled": 0,
      "direction": "SELL",
      "mode": "PULLBACK",
      "zone_low": 107.834,
      "zone_high": 107.89,
      "invalidation": 107.936,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.5,
      "factor_group": "JPY_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 0.8808,
      "pivot": {
        "side": "HIGH",
        "level": 107.862,
        "index": 996,
        "confirmed_index": 998,
        "pivot_utc": "2026-11-16T14:00:00Z",
        "confirmed_utc": "2026-11-16T16:00:00Z"
      },
      "breakout_close_utc": null,
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": true,
      "valid_until_utc": "2026-11-17T17:45:00Z"
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
    "broker_symbol": "AUDJPY",
    "tick_time_utc": "2026-11-16T17:46:06Z",
    "bid": 107.652,
    "ask": 107.665,
    "digits": 3,
    "point": 0.001,
    "spread_points": 13.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -5e-12
  },
  "rtv": {
    "value": 0.6756341275941583,
    "baseline_median": 1301.0,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-16T17:45:00Z"
  }
}
```
