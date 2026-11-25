# AUDCHF candidate evidence

JSON SHA-256: 7e3af9a4c17dd2bdf026daa556fa05635e91203695c529758ad5c7ecd3ea2c9c

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "AUDCHF",
  "as_of_utc": "2026-11-25T07:45:00Z",
  "price_basis": "BID",
  "status": "WATCH",
  "reasons": [
    "NO_VALID_NEARBY_ZONE"
  ],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/AUDCHF/D1.json",
      "sha256": "333408684f7525641d9dc632f97ac456e53cb48ebc2857179d4be5d72958881b",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T22:01:33Z",
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
      "sha256": "9cf6c65049d33445226d7a4e4f760990dd4d7765d9b2de6f9430466cd7477bed",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-25T06:01:14Z",
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
      "sha256": "2a9a465bb508ca3df345142a6205302cdfb8ec3eee994464622a5fc445d57d32",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-25T07:01:12Z",
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
      "sha256": "5098f24068803a34814af4da4fc0c1853c657459904a3e0027ce6b83ca48f979",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-25T07:46:16Z",
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
      "last_closed_bar_utc": "2026-11-24T22:00:00Z",
      "close": 0.55481,
      "ema": {
        "20": 0.5664010940820242,
        "50": 0.5716745012510311,
        "200": 0.5652269138148386
      },
      "ema20_change_5bars": -0.0049824256566812775,
      "atr14": 0.005214112451858275,
      "trend": "SELL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-25T06:00:00Z",
      "close": 0.55118,
      "ema": {
        "20": 0.5574429862810711,
        "50": 0.5613692955906976,
        "200": 0.5698649851521976
      },
      "ema20_change_5bars": -0.0021532555547798538,
      "atr14": 0.0025253323015514747,
      "trend": "SELL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-25T07:00:00Z",
      "close": 0.55012,
      "ema": {
        "20": 0.5540084662938534,
        "50": 0.5560024516143279,
        "200": 0.5614102285175475
      },
      "ema20_change_5bars": -0.001640524792202891,
      "atr14": 0.0013483053635815288,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-25T07:45:00Z",
      "close": 0.54857,
      "ema": {
        "20": 0.5511180462411104,
        "50": 0.5528183872896251,
        "200": 0.5558635189308051
      },
      "ema20_change_5bars": -0.0011782208917323622,
      "atr14": 0.0007759960552739694,
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
  "candidates": [],
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
    "tick_time_utc": "2026-11-25T07:46:09Z",
    "bid": 0.54832,
    "ask": 0.54844,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 12.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -1e-12
  },
  "rtv": {
    "value": 1.6903896103896103,
    "baseline_median": 962.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-25T07:45:00Z"
  }
}
```
