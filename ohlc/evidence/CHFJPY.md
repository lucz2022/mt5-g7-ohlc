# CHFJPY candidate evidence

JSON SHA-256: ea72bf221d1c1a08ed4c13ee583a7c4d83f27cab3dc9962f8ce68b5f9216200a

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "CHFJPY",
  "as_of_utc": "2026-11-16T22:45:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/CHFJPY/D1.json",
      "sha256": "9b32da387b603ee168cab79e6a92e2122d199a5c94765b6a5b6dd99bd06b7b71",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CHFJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T22:02:00Z",
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
      "path": "ohlc/pairs/CHFJPY/H4.json",
      "sha256": "89b34d2b29f82fb167618e2a5b4eeb21b7b36517d3cee74855db526acca7d389",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CHFJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T22:02:00Z",
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
      "path": "ohlc/pairs/CHFJPY/H1.json",
      "sha256": "c34874432b436b5a7cad9f8322ac9f107d636ce5dcb04da36c728866341742e4",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CHFJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T22:02:00Z",
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
      "path": "ohlc/pairs/CHFJPY/M15.json",
      "sha256": "6464b72babcc14642b4a21a3751bcc8fe17e4cd3f9cbf643f9148664c7033695",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CHFJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T22:46:12Z",
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
      "path": "ohlc/pairs/CHFJPY/W1.json",
      "sha256": "bb85980885dbef9789e29e7b35fb41120c4f33c5d02e4d5d1fd60e5b24abc7c3",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CHFJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T02:51:57Z",
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
      "close": 189.745,
      "ema": {
        "20": 191.50557487811062,
        "50": 192.0244953846778,
        "200": 194.61333788801744
      },
      "ema20_change_5bars": -0.3527247267381597,
      "atr14": 1.146698316003975,
      "trend": "SELL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-16T22:00:00Z",
      "close": 189.745,
      "ema": {
        "20": 190.8384032667053,
        "50": 191.5787619701783,
        "200": 191.67404420199483
      },
      "ema20_change_5bars": -0.5619277475047397,
      "atr14": 0.41350378592989867,
      "trend": "SELL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T22:00:00Z",
      "close": 189.745,
      "ema": {
        "20": 190.06220513517945,
        "50": 190.50612965982958,
        "200": 191.60716206211936
      },
      "ema20_change_5bars": -0.14080907014576383,
      "atr14": 0.19064650614567447,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T22:45:00Z",
      "close": 189.669,
      "ema": {
        "20": 189.8222404121875,
        "50": 189.94462768733902,
        "200": 190.49144508670676
      },
      "ema20_change_5bars": -0.0714782435105974,
      "atr14": 0.07604600798420937,
      "trend": "SELL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-14T22:00:00Z",
      "close": 190.275,
      "ema": {
        "20": 193.5624208085477,
        "50": 194.09355222387055,
        "200": 174.81059971566154
      },
      "ema20_change_5bars": -1.518425209568079,
      "atr14": 2.966244970677708,
      "trend": "SELL"
    }
  },
  "candidates": [
    {
      "symbol": "CHFJPY",
      "enabled": 0,
      "direction": "SELL",
      "mode": "BREAKOUT",
      "zone_low": 189.738,
      "zone_high": 189.796,
      "invalidation": 189.844,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.5,
      "factor_group": "JPY_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 0.3619,
      "pivot": {
        "side": "LOW",
        "level": 189.767,
        "index": 996,
        "confirmed_index": 998,
        "pivot_utc": "2026-11-16T19:00:00Z",
        "confirmed_utc": "2026-11-16T21:00:00Z"
      },
      "breakout_close_utc": "2026-11-16T22:00:00Z",
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": true,
      "valid_until_utc": "2026-11-17T22:45:00Z"
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
    "broker_symbol": "CHFJPY",
    "tick_time_utc": "2026-11-16T22:46:07Z",
    "bid": 189.683,
    "ask": 190.068,
    "digits": 3,
    "point": 0.001,
    "spread_points": 385.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -1.9e-11
  },
  "rtv": {
    "value": 1.1815882650480527,
    "baseline_median": 988.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-16T22:45:00Z"
  }
}
```
