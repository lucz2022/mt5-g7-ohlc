# GBPJPY candidate evidence

JSON SHA-256: b481809bc5f30dcd60da2f2973d3d3020a578697bda63556d1afaeee489a474f

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "GBPJPY",
  "as_of_utc": "2026-11-24T20:30:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/GBPJPY/D1.json",
      "sha256": "366877ee917b3901f27ef7da5181f9a30f8a18b5ca347c296a9ab98be0876adb",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-24T03:31:09Z",
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
      "path": "ohlc/pairs/GBPJPY/H4.json",
      "sha256": "5cc29f75b24e714fb6ebe54e7066479b6f77eff9df81c6f8515ef3bfadff628f",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-24T18:01:13Z",
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
      "path": "ohlc/pairs/GBPJPY/H1.json",
      "sha256": "46a9bbfc46945e8b92923d09cd3401ad2ad225486045593cb0179c6c6d88fe24",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-24T20:01:08Z",
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
      "path": "ohlc/pairs/GBPJPY/M15.json",
      "sha256": "360b3e064ad9f072b4bc61434c67812c04e6ed5e55847796c687790a98758a46",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPJPY",
      "digits": 3,
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
      "path": "ohlc/pairs/GBPJPY/W1.json",
      "sha256": "6a408e90929e84caf53bcb30e8ed4a7e202112a764bf0443a2464cccbf5d50e7",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-24T03:31:09Z",
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
      "close": 207.147,
      "ema": {
        "20": 210.14916648282974,
        "50": 210.74646311799674,
        "200": 211.07603142777364
      },
      "ema20_change_5bars": -1.0531121133376757,
      "atr14": 1.397322171768532,
      "trend": "SELL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-24T18:00:00Z",
      "close": 208.913,
      "ema": {
        "20": 208.43594184476777,
        "50": 209.38757723880298,
        "200": 210.49050359491588
      },
      "ema20_change_5bars": -0.15307789885235934,
      "atr14": 0.6594386717145629,
      "trend": "SELL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-24T20:00:00Z",
      "close": 208.856,
      "ema": {
        "20": 208.3168997045825,
        "50": 208.21197647823345,
        "200": 209.3842922096215
      },
      "ema20_change_5bars": 0.32307440826554057,
      "atr14": 0.3118956328386439,
      "trend": "BUY"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-24T20:30:00Z",
      "close": 208.812,
      "ema": {
        "20": 208.80149605438646,
        "50": 208.51611190595943,
        "200": 208.21072030393918
      },
      "ema20_change_5bars": 0.033177573899308754,
      "atr14": 0.1147225806836926,
      "trend": "BUY"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-21T22:00:00Z",
      "close": 207.396,
      "ema": {
        "20": 211.1875317855133,
        "50": 210.13998395465063,
        "200": 193.47745523441128
      },
      "ema20_change_5bars": -0.7611202702997844,
      "atr14": 3.0265769828172733,
      "trend": "NEUTRAL"
    }
  },
  "candidates": [
    {
      "symbol": "GBPJPY",
      "enabled": 0,
      "direction": "SELL",
      "mode": "PULLBACK",
      "zone_low": 209.133,
      "zone_high": 209.227,
      "invalidation": 209.305,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.5,
      "factor_group": "JPY_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 1.0292,
      "pivot": {
        "side": "HIGH",
        "level": 209.18,
        "index": 964,
        "confirmed_index": 966,
        "pivot_utc": "2026-11-23T09:00:00Z",
        "confirmed_utc": "2026-11-23T11:00:00Z"
      },
      "breakout_close_utc": null,
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": false,
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
    "broker_symbol": "GBPJPY",
    "tick_time_utc": "2026-11-24T20:31:05Z",
    "bid": 208.802,
    "ask": 208.816,
    "digits": 3,
    "point": 0.001,
    "spread_points": 14.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -1e-11
  },
  "rtv": {
    "value": 0.581039755351682,
    "baseline_median": 1471.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-24T20:30:00Z"
  }
}
```
