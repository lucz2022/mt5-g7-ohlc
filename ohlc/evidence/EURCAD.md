# EURCAD candidate evidence

JSON SHA-256: 2195d9cbf586cad15a7d7a4bd61dd6bd3b7e04e247df85f78012dabf0b4f05cb

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "EURCAD",
  "as_of_utc": "2026-11-16T19:00:00Z",
  "price_basis": "BID",
  "status": "REJECT",
  "reasons": [
    "D1_H4_TREND_CONFLICT"
  ],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/EURCAD/D1.json",
      "sha256": "7cc9a3c3b657c85e289f882fb45fa4a04929afa442cf616379a12e58382e7a51",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T02:47:58Z",
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
      "path": "ohlc/pairs/EURCAD/H4.json",
      "sha256": "003ac3b5cb42d2d28dd353c99eb8aefcd28f8fc4ae0b62d48f85c44d6a4fec2d",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T18:01:11Z",
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
      "path": "ohlc/pairs/EURCAD/H1.json",
      "sha256": "788348897ddbc981add5bf20251e6833749b8c031c5421251441654436d4d980",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T19:01:10Z",
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
      "path": "ohlc/pairs/EURCAD/M15.json",
      "sha256": "a54f1a5f678cc6bef5e7f4119b3e195dd54b42b4c2a78c5876c4a3019e687787",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T19:01:10Z",
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
      "path": "ohlc/pairs/EURCAD/W1.json",
      "sha256": "65fe3a0981aee60e526d4d2bb3085d4289ec28c81be94740b8a31c9348692821",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T02:48:28Z",
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
      "close": 1.5725099999999999,
      "ema": {
        "20": 1.5766554195088458,
        "50": 1.5863737076200626,
        "200": 1.5989262089473426
      },
      "ema20_change_5bars": 0.0013942741784300772,
      "atr14": 0.007831980327135458,
      "trend": "NEUTRAL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-16T18:00:00Z",
      "close": 1.57325,
      "ema": {
        "20": 1.5757887321371356,
        "50": 1.5756040278924028,
        "200": 1.5811974001955695
      },
      "ema20_change_5bars": -0.001562292466487758,
      "atr14": 0.0027324717969068987,
      "trend": "NEUTRAL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T19:00:00Z",
      "close": 1.5725099999999999,
      "ema": {
        "20": 1.5734675204967636,
        "50": 1.574726411465805,
        "200": 1.5755171446034801
      },
      "ema20_change_5bars": 3.8559615816335935e-05,
      "atr14": 0.0013681843002728304,
      "trend": "NEUTRAL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T19:00:00Z",
      "close": 1.5725099999999999,
      "ema": {
        "20": 1.5733191557320365,
        "50": 1.5733698186356728,
        "200": 1.5747572473195144
      },
      "ema20_change_5bars": -0.0005593424880936393,
      "atr14": 0.0007986777919854542,
      "trend": "SELL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-14T22:00:00Z",
      "close": 1.5725099999999999,
      "ema": {
        "20": 1.5935083095140792,
        "50": 1.5976123857809372,
        "200": 1.5391738522764595
      },
      "ema20_change_5bars": -0.013815846408103738,
      "atr14": 0.01523158178506548,
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
    "broker_symbol": "EURCAD",
    "tick_time_utc": "2026-11-16T19:01:07Z",
    "bid": 1.5723500000000001,
    "ask": 1.57247,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 12.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": 1e-11
  },
  "rtv": {
    "value": 0.793733681462141,
    "baseline_median": 1149.0,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-16T19:00:00Z"
  }
}
```
