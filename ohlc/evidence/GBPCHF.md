# GBPCHF candidate evidence

JSON SHA-256: 37ee5218fafd3c7d217947784732ec3b91e60881a14f7b568012fd70c40370ef

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "GBPCHF",
  "as_of_utc": "2026-11-24T12:30:00Z",
  "price_basis": "BID",
  "status": "REJECT",
  "reasons": [
    "D1_H4_TREND_CONFLICT"
  ],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/GBPCHF/D1.json",
      "sha256": "7ae2b63665a2768377a9e473d9592838969b66f26603e96e765ce965619f3e7b",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPCHF",
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
      "path": "ohlc/pairs/GBPCHF/H4.json",
      "sha256": "cae51442cc0844a9fd8b65eb59dbd11f2213c353d598fb88a41acccf72d66fb7",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPCHF",
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
      "path": "ohlc/pairs/GBPCHF/H1.json",
      "sha256": "c235fdedfd2ff57a39eea3366b21e325b3fdd8ad45fce20d4f149baca89500dd",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T12:01:15Z",
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
      "path": "ohlc/pairs/GBPCHF/M15.json",
      "sha256": "7711f8f33c095c40b648a5330a8381e3065886617c7e43b202b4bf625b9874e2",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T12:31:10Z",
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
      "path": "ohlc/pairs/GBPCHF/W1.json",
      "sha256": "a0ca6ab3e7419b31531a9a69bdf65cc3dd313dc8780b092997b0daba9bcd5e72",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPCHF",
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
      "close": 1.09631,
      "ema": {
        "20": 1.1028225388084119,
        "50": 1.1004981225437673,
        "200": 1.086393206404899
      },
      "ema20_change_5bars": 0.00013866569591791666,
      "atr14": 0.006046227979732171,
      "trend": "NEUTRAL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-24T10:00:00Z",
      "close": 1.09881,
      "ema": {
        "20": 1.1010577687323035,
        "50": 1.1031571040917139,
        "200": 1.102147987975412
      },
      "ema20_change_5bars": -0.002309741588313763,
      "atr14": 0.0028142707577836442,
      "trend": "SELL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-24T12:00:00Z",
      "close": 1.098,
      "ema": {
        "20": 1.0979712176992824,
        "50": 1.0994657297838533,
        "200": 1.1031015834439126
      },
      "ema20_change_5bars": 0.00020650819580225743,
      "atr14": 0.0013791675231691106,
      "trend": "NEUTRAL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-24T12:30:00Z",
      "close": 1.0962,
      "ema": {
        "20": 1.0978543551356428,
        "50": 1.0978138137670292,
        "200": 1.099437977778204
      },
      "ema20_change_5bars": -0.0003862990723806359,
      "atr14": 0.000802071745662959,
      "trend": "NEUTRAL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-21T22:00:00Z",
      "close": 1.09907,
      "ema": {
        "20": 1.0935961986835838,
        "50": 1.0839647025232106,
        "200": 1.1133402108131258
      },
      "ema20_change_5bars": 0.005416982561843975,
      "atr14": 0.012310776803593621,
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
    "broker_symbol": "GBPCHF",
    "tick_time_utc": "2026-11-24T12:31:07Z",
    "bid": 1.09607,
    "ask": 1.0962,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 13.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": 4e-12
  },
  "rtv": {
    "value": 0.9720582447855175,
    "baseline_median": 1270.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-24T12:30:00Z"
  }
}
```
