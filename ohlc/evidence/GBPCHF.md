# GBPCHF candidate evidence

JSON SHA-256: 83c6a3ba793ee593680667057d7101a074dc3c1f2e99f8cc8df0bb66aafa18ec

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "GBPCHF",
  "as_of_utc": "2026-11-16T10:30:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/GBPCHF/D1.json",
      "sha256": "2550c8c9dfdb58385085de9935f65a7b3fe3009c804991085551b196a678dbcf",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T02:49:14Z",
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
      "sha256": "733c88699b78f9b3883ab7300341805e4f0121aefde2270e0f3cb2af01033b29",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T10:01:11Z",
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
      "sha256": "b54e684b3bee53fcfc49dd7cece7857f88858284af3ea64796a346ff71538f09",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T10:01:11Z",
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
      "sha256": "fc15b480f01206bd28ecc96e4c8a28a119b795f9d462afbf3c1753404a07261f",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T10:31:11Z",
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
      "sha256": "4a2dc280fde4d291af28b0902d5bd29086e263cf69206a019f4cc09a458ca90c",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T02:49:48Z",
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
      "close": 1.10816,
      "ema": {
        "20": 1.102165333440125,
        "50": 1.0995189332862467,
        "200": 1.0852634092024027
      },
      "ema20_change_5bars": 0.0017191704118506568,
      "atr14": 0.006177766111648626,
      "trend": "BUY"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-16T10:00:00Z",
      "close": 1.1084,
      "ema": {
        "20": 1.1060243247244614,
        "50": 1.103599605427263,
        "200": 1.101250760814074
      },
      "ema20_change_5bars": 0.0014611510018041063,
      "atr14": 0.002163471604392214,
      "trend": "BUY"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T10:00:00Z",
      "close": 1.1084,
      "ema": {
        "20": 1.1081232109708228,
        "50": 1.1069812413921034,
        "200": 1.1034475987477195
      },
      "ema20_change_5bars": 7.786820013855333e-05,
      "atr14": 0.0010880996391889127,
      "trend": "BUY"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T10:30:00Z",
      "close": 1.10869,
      "ema": {
        "20": 1.1084911249741154,
        "50": 1.108371596660088,
        "200": 1.1070192460275667
      },
      "ema20_change_5bars": 2.5998330185128538e-05,
      "atr14": 0.0005086322876328099,
      "trend": "BUY"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-14T22:00:00Z",
      "close": 1.10816,
      "ema": {
        "20": 1.0930200090713285,
        "50": 1.0833481470649502,
        "200": 1.1135622170071848
      },
      "ema20_change_5bars": 0.005864033357828147,
      "atr14": 0.012152375020037022,
      "trend": "BUY"
    }
  },
  "candidates": [
    {
      "symbol": "GBPCHF",
      "enabled": 0,
      "direction": "BUY",
      "mode": "PULLBACK",
      "zone_low": 1.1072,
      "zone_high": 1.10752,
      "invalidation": 1.10693,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.5,
      "factor_group": "GBP_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 1.0753,
      "pivot": {
        "side": "LOW",
        "level": 1.10736,
        "index": 995,
        "confirmed_index": 997,
        "pivot_utc": "2026-11-16T06:00:00Z",
        "confirmed_utc": "2026-11-16T08:00:00Z"
      },
      "breakout_close_utc": null,
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": true,
      "valid_until_utc": "2026-11-17T10:30:00Z"
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
    "broker_symbol": "GBPCHF",
    "tick_time_utc": "2026-11-16T10:31:05Z",
    "bid": 1.10852,
    "ask": 1.10864,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 12.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -1.2e-11
  },
  "rtv": {
    "value": 0.9679329057720769,
    "baseline_median": 1013.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-16T10:30:00Z"
  }
}
```
