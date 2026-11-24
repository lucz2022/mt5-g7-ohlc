# GBPAUD candidate evidence

JSON SHA-256: 5e0dc56cdcf5f97c30c50c92da1c5e0f37419eafdeca8de926864ddd4c5b2d74

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "GBPAUD",
  "as_of_utc": "2026-11-24T20:30:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/GBPAUD/D1.json",
      "sha256": "4cff3bd0dba080975c78964aa39fd2e50ab93c5bad99728eb7381ab688659c2d",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPAUD",
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
      "path": "ohlc/pairs/GBPAUD/H4.json",
      "sha256": "a6126a3ede94808901a974652536e1a20f8d30819b91f7f98776093878a2dc47",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPAUD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T18:01:14Z",
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
      "sha256": "c0f94dc7432c9917a1592d536db3a43bb629c70d2f1eafd4dec4c26ec3923767",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPAUD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T20:01:09Z",
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
      "sha256": "448ddeac70d522e9d7f67e7d38d98af6729263788f44136fa7adb3f90e7bfd03",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPAUD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T20:31:09Z",
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
      "sha256": "8e4bdefff8fc4aa15391a1bf04a7c7a6477b4e569e595d41112f226cb2f9168f",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPAUD",
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
      "close": 1.9657499999999999,
      "ema": {
        "20": 1.9428303052626574,
        "50": 1.9227787028365384,
        "200": 1.9223786058015713
      },
      "ema20_change_5bars": 0.01502208475389577,
      "atr14": 0.012681388326364054,
      "trend": "BUY"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-24T18:00:00Z",
      "close": 1.9752399999999999,
      "ema": {
        "20": 1.968728277468125,
        "50": 1.9607496066458368,
        "200": 1.932493715878727
      },
      "ema20_change_5bars": 0.001724527474345816,
      "atr14": 0.005904790845394338,
      "trend": "BUY"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-24T20:00:00Z",
      "close": 1.9754800000000001,
      "ema": {
        "20": 1.9719851521372733,
        "50": 1.9702799522564278,
        "200": 1.9607070998925424
      },
      "ema20_change_5bars": 0.002376058199999198,
      "atr14": 0.003055227124604088,
      "trend": "BUY"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-24T20:30:00Z",
      "close": 1.9752800000000001,
      "ema": {
        "20": 1.9745689040791736,
        "50": 1.9729221659533878,
        "200": 1.9702563693239448
      },
      "ema20_change_5bars": 0.0002551156407237798,
      "atr14": 0.0012818951467071765,
      "trend": "BUY"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-21T22:00:00Z",
      "close": 1.97606,
      "ema": {
        "20": 1.9161852178864056,
        "50": 1.929110636085068,
        "200": 1.9263219750354215
      },
      "ema20_change_5bars": 0.01466242579485888,
      "atr14": 0.0251286831077751,
      "trend": "NEUTRAL"
    }
  },
  "candidates": [
    {
      "symbol": "GBPAUD",
      "enabled": 0,
      "direction": "BUY",
      "mode": "BREAKOUT",
      "zone_low": 1.97333,
      "zone_high": 1.97425,
      "invalidation": 1.97257,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.5,
      "factor_group": "GBP_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 0.3371,
      "pivot": {
        "side": "HIGH",
        "level": 1.9737900000000002,
        "index": 991,
        "confirmed_index": 993,
        "pivot_utc": "2026-11-24T12:00:00Z",
        "confirmed_utc": "2026-11-24T14:00:00Z"
      },
      "breakout_close_utc": "2026-11-24T16:00:00Z",
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": true,
      "valid_until_utc": "2026-11-25T20:30:00Z"
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
    "tick_time_utc": "2026-11-24T20:31:06Z",
    "bid": 1.97481,
    "ask": 1.97496,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 15.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -9e-12
  },
  "rtv": {
    "value": 0.5871852087982149,
    "baseline_median": 1568.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-24T20:30:00Z"
  }
}
```
