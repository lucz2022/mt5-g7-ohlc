# CADJPY candidate evidence

JSON SHA-256: a539f9ff68d3dab9716e5dcaddaef0fdab19b490ff94e6d7f29568ef7d0aabf4

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "CADJPY",
  "as_of_utc": "2026-11-25T09:00:00Z",
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
      "sha256": "448011fdbfed7891cfbf158c33bc82125f612f9621ccfb6edda650497e33f576",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CADJPY",
      "digits": 3,
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
      "path": "ohlc/pairs/CADJPY/H1.json",
      "sha256": "390bb40a51831bb04ddccd994c63e9808623b1eaf349e43f763531a172c64b6e",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CADJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-25T09:01:11Z",
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
      "sha256": "0ce42cbef80bd9706baaf674cd14ff1d5ef1dcc33166f91a6d98c0f2cb98f424",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CADJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-25T09:01:11Z",
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
      "last_closed_bar_utc": "2026-11-25T06:00:00Z",
      "close": 111.637,
      "ema": {
        "20": 111.21696336610921,
        "50": 111.3889393338478,
        "200": 111.89510307745327
      },
      "ema20_change_5bars": 0.1911740990039874,
      "atr14": 0.29903131853778486,
      "trend": "NEUTRAL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-25T09:00:00Z",
      "close": 111.638,
      "ema": {
        "20": 111.46393290314245,
        "50": 111.26135530530335,
        "200": 111.38724225941903
      },
      "ema20_change_5bars": 0.06517807239579554,
      "atr14": 0.16608685275330892,
      "trend": "BUY"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-25T09:00:00Z",
      "close": 111.638,
      "ema": {
        "20": 111.55559788681066,
        "50": 111.53846478956902,
        "200": 111.25953562471886
      },
      "ema20_change_5bars": -0.005277417901027093,
      "atr14": 0.07723131652125759,
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
    "tick_time_utc": "2026-11-25T09:01:07Z",
    "bid": 111.622,
    "ask": 111.634,
    "digits": 3,
    "point": 0.001,
    "spread_points": 12.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -0.0
  },
  "rtv": {
    "value": 1.4094368340943684,
    "baseline_median": 985.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-25T09:00:00Z"
  }
}
```
