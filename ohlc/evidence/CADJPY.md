# CADJPY candidate evidence

JSON SHA-256: 0de9b27132f4f49010e436916af55fb5cbd09c310d4f110df9e4b918422f458d

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "CADJPY",
  "as_of_utc": "2026-11-25T03:30:00Z",
  "price_basis": "BID",
  "status": "REJECT",
  "reasons": [
    "D1_H4_TREND_CONFLICT"
  ],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/CADJPY/D1.json",
      "sha256": "eff833fb26448f58086f1dd927111a23c40ce6149d5bab9892b454b2cd387041",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CADJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-24T22:01:30Z",
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
      "path": "ohlc/pairs/CADJPY/H4.json",
      "sha256": "ab16c33aaa102cf6bfd60246a9564ced284466e26c82debf3b0ea6fc0bf18f2c",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CADJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-25T02:01:09Z",
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
      "path": "ohlc/pairs/CADJPY/H1.json",
      "sha256": "edc6ead5ff129b29f0fca0bfd0228d4151c19db4ac6afd321f2171074ce446da",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CADJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-25T03:01:14Z",
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
      "path": "ohlc/pairs/CADJPY/M15.json",
      "sha256": "a0c0e51f2b87dfc4143aaf5a8ec319622df09fab3f6a394286e467d0ecace7ef",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CADJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-25T03:31:09Z",
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
      "path": "ohlc/pairs/CADJPY/W1.json",
      "sha256": "f0ecf3fd5838ee98bab6e022d48bde69a81a57199b38a3a205eeb3ad31f4877b",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CADJPY",
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
      "last_closed_bar_utc": "2026-11-24T22:00:00Z",
      "close": 111.602,
      "ema": {
        "20": 111.68591864517174,
        "50": 112.06405179917932,
        "200": 112.82233383209783
      },
      "ema20_change_5bars": -0.39342634170664326,
      "atr14": 0.7194704020621,
      "trend": "SELL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-25T02:00:00Z",
      "close": 111.616,
      "ema": {
        "20": 111.17274898359439,
        "50": 111.37881440939677,
        "200": 111.89724925474762
      },
      "ema20_change_5bars": 0.16950821468861932,
      "atr14": 0.3001875738099228,
      "trend": "NEUTRAL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-25T03:00:00Z",
      "close": 111.526,
      "ema": {
        "20": 111.37936060240419,
        "50": 111.17770516079806,
        "200": 111.37586298367079
      },
      "ema20_change_5bars": 0.13638920197169568,
      "atr14": 0.1519847886943007,
      "trend": "BUY"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-25T03:30:00Z",
      "close": 111.573,
      "ema": {
        "20": 111.5950685567284,
        "50": 111.50037508809763,
        "200": 111.18196848319215
      },
      "ema20_change_5bars": -0.009681027033394685,
      "atr14": 0.06466476028821376,
      "trend": "NEUTRAL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-21T22:00:00Z",
      "close": 110.512,
      "ema": {
        "20": 112.50144470847931,
        "50": 112.57146482007963,
        "200": 107.57237077794156
      },
      "ema20_change_5bars": -0.4787486155133962,
      "atr14": 1.6000685422802479,
      "trend": "SELL"
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
    "broker_symbol": "CADJPY",
    "tick_time_utc": "2026-11-25T03:31:07Z",
    "bid": 111.586,
    "ask": 111.6,
    "digits": 3,
    "point": 0.001,
    "spread_points": 14.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": 4e-12
  },
  "rtv": {
    "value": 0.9239766081871345,
    "baseline_median": 1026.0,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-25T03:30:00Z"
  }
}
```
