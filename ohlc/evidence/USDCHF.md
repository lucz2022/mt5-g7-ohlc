# USDCHF candidate evidence

JSON SHA-256: c9c2e7e5869528bc804006a49c8d9ec664feea600ca6a1594c76f2ef572b6e30

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "USDCHF",
  "as_of_utc": "2026-11-16T07:15:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/USDCHF/D1.json",
      "sha256": "c9af53559c07e3189a926a9c93c074b72d8d23136a5b95ac89f1065343b66ff8",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T02:38:22Z",
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
      "sha256": "8f86db2a6cb5c86e8f0900f5a32142ce2517772844591653353d3ff7e1d9beb1",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T06:01:10Z",
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
      "sha256": "727a251669dd3d15dc1b06aa00e42f867f534349c995f9fd9111968c2030cdad",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T07:01:11Z",
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
      "sha256": "e7965a56ba9c630472bffe7df2f33cfdfd3dd63d91eec6cf488e41565a8f52c7",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T07:16:06Z",
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
      "sha256": "1c53bb4427b1804806675a995580b07039d5f6814eb08b314f7b05c654bcec12",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T02:33:06Z",
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
      "close": 0.83881,
      "ema": {
        "20": 0.8265650501285572,
        "50": 0.8234880511700068,
        "200": 0.8113353605167671
      },
      "ema20_change_5bars": 0.003098551198146726,
      "atr14": 0.0060289963953888154,
      "trend": "BUY"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-16T06:00:00Z",
      "close": 0.83859,
      "ema": {
        "20": 0.8338970525648317,
        "50": 0.828516845373337,
        "200": 0.8251859336177929
      },
      "ema20_change_5bars": 0.0031680114897044698,
      "atr14": 0.002119410840582874,
      "trend": "BUY"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T07:00:00Z",
      "close": 0.83947,
      "ema": {
        "20": 0.8384825378736286,
        "50": 0.8361933256150165,
        "200": 0.8284384435693255
      },
      "ema20_change_5bars": 0.00045115186998956336,
      "atr14": 0.0009700096265578907,
      "trend": "BUY"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T07:15:00Z",
      "close": 0.83927,
      "ema": {
        "20": 0.8390539122157677,
        "50": 0.8388861925068363,
        "200": 0.8361973721557309
      },
      "ema20_change_5bars": 3.35716662464014e-05,
      "atr14": 0.00039630508688041303,
      "trend": "BUY"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-14T22:00:00Z",
      "close": 0.83881,
      "ema": {
        "20": 0.8177293760771989,
        "50": 0.8104723925673032,
        "200": 0.8493852612108518
      },
      "ema20_change_5bars": 0.00614406048752969,
      "atr14": 0.012704237441014843,
      "trend": "BUY"
    }
  },
  "candidates": [
    {
      "symbol": "USDCHF",
      "enabled": 0,
      "direction": "BUY",
      "mode": "PULLBACK",
      "zone_low": 0.8375,
      "zone_high": 0.8378,
      "invalidation": 0.83726,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.75,
      "factor_group": "USD_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 1.5154,
      "pivot": {
        "side": "LOW",
        "level": 0.83765,
        "index": 991,
        "confirmed_index": 993,
        "pivot_utc": "2026-11-15T23:00:00Z",
        "confirmed_utc": "2026-11-16T01:00:00Z"
      },
      "breakout_close_utc": null,
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": true,
      "valid_until_utc": "2026-11-17T07:15:00Z"
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
    "tick_time_utc": "2026-11-16T07:16:06Z",
    "bid": 0.83905,
    "ask": 0.83913,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 8.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -8e-12
  },
  "rtv": {
    "value": 1.220216606498195,
    "baseline_median": 415.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-16T07:15:00Z"
  }
}
```
