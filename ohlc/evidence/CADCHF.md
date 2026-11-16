# CADCHF candidate evidence

JSON SHA-256: 52a43ea0dc2f8e5fb6ea8de14de3a58e5b1aff3d4c46283b779d7703e561ef55

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "CADCHF",
  "as_of_utc": "2026-11-16T22:15:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/CADCHF/D1.json",
      "sha256": "746f1fed393a49740510e6f35b1177752fda8dff5bfdff58d4a2964d2bed64cc",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CADCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T22:02:00Z",
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
      "sha256": "19c9f0a1645ff4da02731436054919ff8eea5b29646bd2dfe379dc696732cfdf",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CADCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T22:01:59Z",
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
      "sha256": "22ddd1fe7689452b097eb340ef8e3f389a946cd10f3a7e7626ba75a619afed2a",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CADCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T22:01:59Z",
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
      "sha256": "45a47e7838b066ccc25bed91b983c85b4450141ad1c99c00584c8dd770556c07",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CADCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T22:16:11Z",
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
      "sha256": "48d412bc237770d55ab36dccd70ba1494ec0f1158c17863024ce1285fc05c080",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CADCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T02:50:55Z",
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
      "close": 0.58752,
      "ema": {
        "20": 0.5855097946797473,
        "50": 0.5848528756875686,
        "200": 0.5804243855194827
      },
      "ema20_change_5bars": 0.00016158640481533926,
      "atr14": 0.0037426415422761768,
      "trend": "BUY"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-16T22:00:00Z",
      "close": 0.58752,
      "ema": {
        "20": 0.5863197389849835,
        "50": 0.5852594283935763,
        "200": 0.5854125608758053
      },
      "ema20_change_5bars": 0.0007694822107955357,
      "atr14": 0.0013218378408749812,
      "trend": "BUY"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T22:00:00Z",
      "close": 0.58752,
      "ema": {
        "20": 0.5874925687050713,
        "50": 0.5869796418100277,
        "200": 0.5852067719333843
      },
      "ema20_change_5bars": -3.6410349070203907e-06,
      "atr14": 0.0005908664283963231,
      "trend": "NEUTRAL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T22:15:00Z",
      "close": 0.58714,
      "ema": {
        "20": 0.5874421538492431,
        "50": 0.587450670374747,
        "200": 0.5869698339299216
      },
      "ema20_change_5bars": 4.0463093805787054e-05,
      "atr14": 0.00025030402368100737,
      "trend": "NEUTRAL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-14T22:00:00Z",
      "close": 0.58774,
      "ema": {
        "20": 0.5822238409311021,
        "50": 0.5805730921228468,
        "200": 0.6233603591580497
      },
      "ema20_change_5bars": 0.0024891204976482673,
      "atr14": 0.007554317428246551,
      "trend": "BUY"
    }
  },
  "candidates": [
    {
      "symbol": "CADCHF",
      "enabled": 0,
      "direction": "BUY",
      "mode": "PULLBACK",
      "zone_low": 0.58608,
      "zone_high": 0.58626,
      "invalidation": 0.58593,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.5,
      "factor_group": "CAD_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 1.4893,
      "pivot": {
        "side": "LOW",
        "level": 0.58617,
        "index": 976,
        "confirmed_index": 978,
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
      "m15_direction_confirmed": false,
      "valid_until_utc": "2026-11-17T22:15:00Z"
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
    "broker_symbol": "CADCHF",
    "tick_time_utc": "2026-11-16T22:16:06Z",
    "bid": 0.58707,
    "ask": 0.58769,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 62.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -6e-12
  },
  "rtv": {
    "value": 0.056372549019607844,
    "baseline_median": 408.0,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-16T22:15:00Z"
  }
}
```
