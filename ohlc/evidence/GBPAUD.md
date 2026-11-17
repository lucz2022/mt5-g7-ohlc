# GBPAUD candidate evidence

JSON SHA-256: 59ce8591c9884d0ad84111d18e0e1a5b442e9786d183637872dfc147c7ddf6c8

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "GBPAUD",
  "as_of_utc": "2026-11-17T03:00:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/GBPAUD/D1.json",
      "sha256": "94809a644369ccf0bb38d38b5588380af145a2d913ce8d5060a8a60faa512ce6",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPAUD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T22:01:29Z",
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
      "path": "ohlc/pairs/GBPAUD/H4.json",
      "sha256": "806a5479c3b3c9e6d29090603b45808b1b8d4cf2e067afe233bc373a414fe190",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPAUD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-17T02:01:10Z",
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
      "path": "ohlc/pairs/GBPAUD/H1.json",
      "sha256": "b67b8002902d1842d0a197ea531e073a14e66e30e123b481ced06ab0a6b502c8",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPAUD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-17T03:01:13Z",
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
      "path": "ohlc/pairs/GBPAUD/M15.json",
      "sha256": "1bb02cae975f78eeec3384f827fe9a16505758bffd5742fab697cbcd4a358092",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPAUD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-17T03:01:12Z",
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
      "path": "ohlc/pairs/GBPAUD/W1.json",
      "sha256": "58c8558331ff9a299cd2d34dc93d2a2b7d53a16a7ad7a4cd8e194ce764d834df",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPAUD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T02:35:05Z",
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
      "close": 1.95669,
      "ema": {
        "20": 1.9278082205087617,
        "50": 1.9132843169576947,
        "200": 1.920093106091427
      },
      "ema20_change_5bars": 0.012619268739040956,
      "atr14": 0.012218010695699682,
      "trend": "BUY"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-17T02:00:00Z",
      "close": 1.95622,
      "ema": {
        "20": 1.9496780969488257,
        "50": 1.9413087986539548,
        "200": 1.9187615944082754
      },
      "ema20_change_5bars": 0.0037433604189875958,
      "atr14": 0.00441830771377702,
      "trend": "BUY"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-17T03:00:00Z",
      "close": 1.95631,
      "ema": {
        "20": 1.9552574524768027,
        "50": 1.9520194198599672,
        "200": 1.941210711201414
      },
      "ema20_change_5bars": 0.001018493332615611,
      "atr14": 0.0022266700204729576,
      "trend": "BUY"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-17T03:00:00Z",
      "close": 1.95631,
      "ema": {
        "20": 1.956508663678869,
        "50": 1.9560594380055307,
        "200": 1.9520156484991207
      },
      "ema20_change_5bars": -0.0002489786123049953,
      "atr14": 0.001265762799364054,
      "trend": "NEUTRAL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-14T22:00:00Z",
      "close": 1.9498,
      "ema": {
        "20": 1.9098826092428693,
        "50": 1.9271943336372839,
        "200": 1.9259623831947004
      },
      "ema20_change_5bars": 0.010126891668001292,
      "atr14": 0.02462473565525379,
      "trend": "NEUTRAL"
    }
  },
  "candidates": [
    {
      "symbol": "GBPAUD",
      "enabled": 0,
      "direction": "BUY",
      "mode": "PULLBACK",
      "zone_low": 1.95219,
      "zone_high": 1.95285,
      "invalidation": 1.95163,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.5,
      "factor_group": "GBP_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 1.5539,
      "pivot": {
        "side": "LOW",
        "level": 1.95252,
        "index": 980,
        "confirmed_index": 982,
        "pivot_utc": "2026-11-16T08:00:00Z",
        "confirmed_utc": "2026-11-16T10:00:00Z"
      },
      "breakout_close_utc": null,
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": false,
      "valid_until_utc": "2026-11-18T03:00:00Z"
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
    "broker_symbol": "GBPAUD",
    "tick_time_utc": "2026-11-17T03:01:10Z",
    "bid": 1.95613,
    "ask": 1.95628,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 15.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -9e-12
  },
  "rtv": {
    "value": 0.9465126230209671,
    "baseline_median": 1168.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-17T03:00:00Z"
  }
}
```
