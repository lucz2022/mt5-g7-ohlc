# AUDUSD candidate evidence

JSON SHA-256: e0985279b81a4cbd9ded4e6f9ace648a54a891cd536f7e106a53efafde11408c

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "AUDUSD",
  "as_of_utc": "2026-11-17T02:45:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/AUDUSD/D1.json",
      "sha256": "07906ed2f75436c4139c722f7dd6b42c1e3d6971984c399fbcddc1d2db17ff18",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T22:01:15Z",
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
      "path": "ohlc/pairs/AUDUSD/H4.json",
      "sha256": "4108ff43c67409f59ef0799bfaf476979ff7fb6242e84aeb69a4d077ca346f1a",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-17T02:01:09Z",
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
      "path": "ohlc/pairs/AUDUSD/H1.json",
      "sha256": "c4e3dbffdde795797d84dc9aff510165f07053d6d8fb524797c09fca1c0a629d",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-17T02:01:09Z",
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
      "path": "ohlc/pairs/AUDUSD/M15.json",
      "sha256": "49cade40ec37ef2108cea41a7424145531f43b3fa0082eaddbf0731dc582ce44",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-17T02:46:10Z",
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
      "path": "ohlc/pairs/AUDUSD/W1.json",
      "sha256": "25c2a0c8870e04b454e6ce7a4a1c8690f066cf44b1f36ee497683c1b2e99101f",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T02:33:12Z",
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
      "close": 0.67377,
      "ema": {
        "20": 0.6909584772695866,
        "50": 0.6975735353922017,
        "200": 0.6970384543805297
      },
      "ema20_change_5bars": -0.007161004905882229,
      "atr14": 0.005390982454549201,
      "trend": "SELL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-17T02:00:00Z",
      "close": 0.67368,
      "ema": {
        "20": 0.6786588333376622,
        "50": 0.6848785306063457,
        "200": 0.6952132506317438
      },
      "ema20_change_5bars": -0.002767965798066707,
      "atr14": 0.0018235681966293873,
      "trend": "SELL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-17T02:00:00Z",
      "close": 0.67368,
      "ema": {
        "20": 0.6746334140265653,
        "50": 0.6768172268254844,
        "200": 0.6850408286353775
      },
      "ema20_change_5bars": -0.0006700166114299577,
      "atr14": 0.0008898057233788137,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-17T02:45:00Z",
      "close": 0.674,
      "ema": {
        "20": 0.6736934132431944,
        "50": 0.6740798328881842,
        "200": 0.6767681765266192
      },
      "ema20_change_5bars": 9.611799775255392e-05,
      "atr14": 0.0004681404424389883,
      "trend": "NEUTRAL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-14T22:00:00Z",
      "close": 0.67708,
      "ema": {
        "20": 0.6998130798434226,
        "50": 0.6940327483605638,
        "200": 0.6827272344123759
      },
      "ema20_change_5bars": -0.005248907040624307,
      "atr14": 0.011269457735274473,
      "trend": "NEUTRAL"
    }
  },
  "candidates": [
    {
      "symbol": "AUDUSD",
      "enabled": 0,
      "direction": "SELL",
      "mode": "BREAKOUT",
      "zone_low": 0.67405,
      "zone_high": 0.67431,
      "invalidation": 0.67453,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.75,
      "factor_group": "USD_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 0.0562,
      "pivot": {
        "side": "LOW",
        "level": 0.67418,
        "index": 989,
        "confirmed_index": 991,
        "pivot_utc": "2026-11-16T16:00:00Z",
        "confirmed_utc": "2026-11-16T18:00:00Z"
      },
      "breakout_close_utc": "2026-11-16T19:00:00Z",
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": false,
      "valid_until_utc": "2026-11-18T02:45:00Z"
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
    "broker_symbol": "AUDUSD",
    "tick_time_utc": "2026-11-17T02:46:08Z",
    "bid": 0.67398,
    "ask": 0.67407,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 9.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": 8e-12
  },
  "rtv": {
    "value": 2.050171037628278,
    "baseline_median": 438.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-17T02:45:00Z"
  }
}
```
