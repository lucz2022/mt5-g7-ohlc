# EURAUD candidate evidence

JSON SHA-256: c110e682b043910a46714468df7657ebc2b6b81045a2f30ea2e579ffaf3e9707

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "EURAUD",
  "as_of_utc": "2026-11-25T06:45:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/EURAUD/D1.json",
      "sha256": "008800703d6472091e0451211be8ed519c22c1ec4a20a683cd556aa0d9edaada",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURAUD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T22:01:31Z",
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
      "sha256": "63812ed6574367350a0391bc11605b0ca50b5dc0f2df2c30d6000d8b04d2572b",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURAUD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-25T06:01:13Z",
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
      "sha256": "21a2fdb34573b9145fa7077506bd40d110e94faef08eb74d21f32513242813ff",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURAUD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-25T06:01:13Z",
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
      "sha256": "787ccb4fd30e693202258a2c215e96a66a85008202f6c0856a27776c286896cd",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURAUD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-25T06:46:15Z",
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
      "last_closed_bar_utc": "2026-11-24T22:00:00Z",
      "close": 1.65111,
      "ema": {
        "20": 1.6280172937765993,
        "50": 1.620164464450577,
        "200": 1.6418469332847465
      },
      "ema20_change_5bars": 0.01258823167920231,
      "atr14": 0.011420826759450877,
      "trend": "BUY"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-25T06:00:00Z",
      "close": 1.6602700000000001,
      "ema": {
        "20": 1.64900127494951,
        "50": 1.6408828592201392,
        "200": 1.6223002165539988
      },
      "ema20_change_5bars": 0.0029631080173442292,
      "atr14": 0.005768935134212922,
      "trend": "BUY"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-25T06:00:00Z",
      "close": 1.6602700000000001,
      "ema": {
        "20": 1.652907006038392,
        "50": 1.6504378917090685,
        "200": 1.6405152760065886
      },
      "ema20_change_5bars": 0.002909274021860142,
      "atr14": 0.0032283845266012383,
      "trend": "BUY"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-25T06:45:00Z",
      "close": 1.66246,
      "ema": {
        "20": 1.6580636960676236,
        "50": 1.6548413331353713,
        "200": 1.6506099674187618
      },
      "ema20_change_5bars": 0.0019334829083446081,
      "atr14": 0.001635388076242326,
      "trend": "BUY"
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
      "mode": "BREAKOUT",
      "zone_low": 1.65478,
      "zone_high": 1.65574,
      "invalidation": 1.65397,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.5,
      "factor_group": "EUR_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 2.0815,
      "pivot": {
        "side": "HIGH",
        "level": 1.65526,
        "index": 986,
        "confirmed_index": 988,
        "pivot_utc": "2026-11-24T17:00:00Z",
        "confirmed_utc": "2026-11-24T19:00:00Z"
      },
      "breakout_close_utc": "2026-11-25T03:00:00Z",
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": true,
      "valid_until_utc": "2026-11-26T06:45:00Z"
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
    "tick_time_utc": "2026-11-25T06:46:12Z",
    "bid": 1.66263,
    "ask": 1.66279,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 16.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": 6e-12
  },
  "rtv": {
    "value": 1.1461254612546126,
    "baseline_median": 1355.0,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-25T06:45:00Z"
  }
}
```
