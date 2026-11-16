# USDCAD candidate evidence

JSON SHA-256: 60139594bb844c38d9e9649e219c165d294413e67a12d4670c40625d1537982f

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "USDCAD",
  "as_of_utc": "2026-11-16T18:15:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/USDCAD/D1.json",
      "sha256": "74f748c287362e89403fd7d538502e41622f2bed6872601e09290bcb128a61dd",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDCAD",
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
      "path": "ohlc/pairs/USDCAD/H4.json",
      "sha256": "321b220fd841187957959babd485aa392f6fda3756f01cf135f2b2b708dfb0e9",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T18:01:08Z",
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
      "path": "ohlc/pairs/USDCAD/H1.json",
      "sha256": "083f2f592e91c772209566a015255c3f0f9a29e48e7fb91702be9c4beaf42b55",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T18:01:08Z",
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
      "path": "ohlc/pairs/USDCAD/M15.json",
      "sha256": "a1b7d9d3c746175b1110c0b9e30fa7fca6882db9b01b1b946198189cbd8d07f2",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T18:16:08Z",
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
      "path": "ohlc/pairs/USDCAD/W1.json",
      "sha256": "57c78190aece8ccfba957e4391f6b7e8e9a4e7f85cc720e279a7f77768941a24",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T02:33:08Z",
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
      "close": 1.42676,
      "ema": {
        "20": 1.4121669894715,
        "50": 1.408249471969954,
        "200": 1.3978003110810187
      },
      "ema20_change_5bars": 0.006612187128159253,
      "atr14": 0.006603674618265439,
      "trend": "BUY"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-16T18:00:00Z",
      "close": 1.4297,
      "ema": {
        "20": 1.4251593855274616,
        "50": 1.41806110023617,
        "200": 1.4104228010609952
      },
      "ema20_change_5bars": 0.0022952358419718877,
      "atr14": 0.0021769058289051804,
      "trend": "BUY"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T18:00:00Z",
      "close": 1.4297,
      "ema": {
        "20": 1.4285862734266048,
        "50": 1.4268869434625437,
        "200": 1.4178559478148485
      },
      "ema20_change_5bars": 0.0010234531323152218,
      "atr14": 0.0010701073322948835,
      "trend": "BUY"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T18:15:00Z",
      "close": 1.43012,
      "ema": {
        "20": 1.4297655339134656,
        "50": 1.4290482713789716,
        "200": 1.4268577564137217
      },
      "ema20_change_5bars": -7.321412589766929e-05,
      "atr14": 0.0006653681095071452,
      "trend": "NEUTRAL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-14T22:00:00Z",
      "close": 1.42676,
      "ema": {
        "20": 1.4042381780396131,
        "50": 1.3956302913862237,
        "200": 1.3661890530135425
      },
      "ema20_change_5bars": 0.004570297066452511,
      "atr14": 0.015118582720485647,
      "trend": "BUY"
    }
  },
  "candidates": [
    {
      "symbol": "USDCAD",
      "enabled": 0,
      "direction": "BUY",
      "mode": "BREAKOUT",
      "zone_low": 1.42893,
      "zone_high": 1.42925,
      "invalidation": 1.42866,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.75,
      "factor_group": "USD_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 0.813,
      "pivot": {
        "side": "HIGH",
        "level": 1.42909,
        "index": 991,
        "confirmed_index": 993,
        "pivot_utc": "2026-11-16T10:00:00Z",
        "confirmed_utc": "2026-11-16T12:00:00Z"
      },
      "breakout_close_utc": "2026-11-16T14:00:00Z",
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": false,
      "valid_until_utc": "2026-11-17T18:15:00Z"
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
    "broker_symbol": "USDCAD",
    "tick_time_utc": "2026-11-16T18:16:07Z",
    "bid": 1.43015,
    "ask": 1.43025,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 10.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": 1e-12
  },
  "rtv": {
    "value": 0.727932285368803,
    "baseline_median": 827.0,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-16T18:15:00Z"
  }
}
```
