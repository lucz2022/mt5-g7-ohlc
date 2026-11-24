# EURJPY candidate evidence

JSON SHA-256: 7bb073cee4a224ba5e303ceb032b33359def19115dea1f667d8397b402f886c9

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "EURJPY",
  "as_of_utc": "2026-11-24T08:00:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/EURJPY/D1.json",
      "sha256": "638a8af9549a53dd62cc7e4a080a1402c492316c5c519fea7bfac8c12f983e54",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURJPY",
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
      "path": "ohlc/pairs/EURJPY/H4.json",
      "sha256": "6b48538bfa27db5707ebf33467341831ceb025ac37bb090d30f5f330fa3f4e0b",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-24T06:01:12Z",
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
      "path": "ohlc/pairs/EURJPY/H1.json",
      "sha256": "7d16afb6859f15a0f6348271d3882c0dd4f580ec97bec3a97f287540831ac1dc",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-24T08:01:12Z",
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
      "path": "ohlc/pairs/EURJPY/M15.json",
      "sha256": "4b58af2221c915eb7047e2c34a3a1a8d2533ab1729ebce4f04376cbf45ceab4d",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-24T08:01:12Z",
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
      "path": "ohlc/pairs/EURJPY/W1.json",
      "sha256": "8eab442550f84a641719f42bcd7f6ffe0d7fe97be51cc05f732d70b8926fc22c",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURJPY",
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
      "close": 173.331,
      "ema": {
        "20": 175.84349002410806,
        "50": 177.46578566113328,
        "200": 180.27363518368958
      },
      "ema20_change_5bars": -0.9393252070073856,
      "atr14": 1.1817125338410284,
      "trend": "SELL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-24T06:00:00Z",
      "close": 173.684,
      "ema": {
        "20": 174.32438273020082,
        "50": 175.11079522846455,
        "200": 176.67598803157512
      },
      "ema20_change_5bars": -0.5026313256975925,
      "atr14": 0.5376567182483213,
      "trend": "SELL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-24T08:00:00Z",
      "close": 173.774,
      "ema": {
        "20": 173.6727056452921,
        "50": 174.04544448011538,
        "200": 175.11140625346133
      },
      "ema20_change_5bars": -0.024570177945662408,
      "atr14": 0.23316982370454548,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-24T08:00:00Z",
      "close": 173.774,
      "ema": {
        "20": 173.62804258306696,
        "50": 173.58380244456555,
        "200": 174.0492786577626
      },
      "ema20_change_5bars": 0.0751442516406371,
      "atr14": 0.09667178148937057,
      "trend": "BUY"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-21T22:00:00Z",
      "close": 173.878,
      "ema": {
        "20": 179.10172671931758,
        "50": 179.80484381829976,
        "200": 165.9832397052049
      },
      "ema20_change_5bars": -2.3316194328724293,
      "atr14": 2.4774870993911042,
      "trend": "SELL"
    }
  },
  "candidates": [
    {
      "symbol": "EURJPY",
      "enabled": 0,
      "direction": "SELL",
      "mode": "PULLBACK",
      "zone_low": 174.391,
      "zone_high": 174.461,
      "invalidation": 174.519,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.5,
      "factor_group": "JPY_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 2.6461,
      "pivot": {
        "side": "HIGH",
        "level": 174.426,
        "index": 982,
        "confirmed_index": 984,
        "pivot_utc": "2026-11-23T15:00:00Z",
        "confirmed_utc": "2026-11-23T17:00:00Z"
      },
      "breakout_close_utc": null,
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": false,
      "valid_until_utc": "2026-11-25T08:00:00Z"
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
    "broker_symbol": "EURJPY",
    "tick_time_utc": "2026-11-24T08:01:09Z",
    "bid": 173.752,
    "ask": 173.771,
    "digits": 3,
    "point": 0.001,
    "spread_points": 19.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": 2.3e-11
  },
  "rtv": {
    "value": 1.4775374376039934,
    "baseline_median": 901.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-24T08:00:00Z"
  }
}
```
