# CADCHF candidate evidence

JSON SHA-256: 60d4170432a574f178da106de31d3f873498429e03ade046c4a4f9ffd16bd17c

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "CADCHF",
  "as_of_utc": "2026-11-25T12:45:00Z",
  "price_basis": "BID",
  "status": "REJECT",
  "reasons": [
    "D1_H4_TREND_CONFLICT"
  ],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/CADCHF/D1.json",
      "sha256": "d21e1fd50cf81eba0816e5d1eaae84a8fd8215a3bc8cbb64d40d63e4ce8d6f4d",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CADCHF",
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
      "path": "ohlc/pairs/CADCHF/H4.json",
      "sha256": "995dbb7a0787c71e938d2d0feb1318923ace5d17dabcadd0aa1a0089337622ea",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CADCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-25T10:01:14Z",
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
      "path": "ohlc/pairs/CADCHF/H1.json",
      "sha256": "da7b02a1cfddd43c61180df69555e8e7750de73728cb8ffe0d6cf3cbe435f6e5",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CADCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-25T12:31:12Z",
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
      "path": "ohlc/pairs/CADCHF/M15.json",
      "sha256": "58064e8c457ec760ed4f571472a8117d4ec3e3523f9871b0e1e43b5394d48b19",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CADCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-25T12:46:13Z",
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
      "path": "ohlc/pairs/CADCHF/W1.json",
      "sha256": "e596cdd2887d72f322752a944029e4270e21df5e9ad6530da6fe9c890e1ff7a7",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CADCHF",
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
      "close": 0.58557,
      "ema": {
        "20": 0.5861002141183209,
        "50": 0.5852967865576129,
        "200": 0.5808168718313945
      },
      "ema20_change_5bars": 0.0003618284556924367,
      "atr14": 0.0036039052313492467,
      "trend": "BUY"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-25T10:00:00Z",
      "close": 0.58398,
      "ema": {
        "20": 0.5859467006940061,
        "50": 0.5862488373183558,
        "200": 0.5858470928194321
      },
      "ema20_change_5bars": -0.00048193362598314415,
      "atr14": 0.0015315868713675514,
      "trend": "SELL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-25T12:00:00Z",
      "close": 0.58279,
      "ema": {
        "20": 0.5847925170290795,
        "50": 0.5854148298945103,
        "200": 0.5861911616882198
      },
      "ema20_change_5bars": -0.0008165680805953812,
      "atr14": 0.0008351184664681814,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-25T12:45:00Z",
      "close": 0.58164,
      "ema": {
        "20": 0.5833169759480077,
        "50": 0.5842862515126589,
        "200": 0.5853486879315876
      },
      "ema20_change_5bars": -0.0006429525468683028,
      "atr14": 0.000565654246925504,
      "trend": "SELL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-21T22:00:00Z",
      "close": 0.58562,
      "ema": {
        "20": 0.5825472846519506,
        "50": 0.5807710371932108,
        "200": 0.6230841217488567
      },
      "ema20_change_5bars": 0.002515870926442787,
      "atr14": 0.007394723325907994,
      "trend": "BUY"
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
    "broker_symbol": "CADCHF",
    "tick_time_utc": "2026-11-25T12:46:08Z",
    "bid": 0.58144,
    "ask": 0.58155,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 11.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -5e-12
  },
  "rtv": {
    "value": 1.204929256047467,
    "baseline_median": 1095.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-25T12:45:00Z"
  }
}
```
