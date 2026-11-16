# EURCAD candidate evidence

JSON SHA-256: 17837b74397891c06704e97f42ce895f00c05779f67a2e6f46ec0cbdff7aecff

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "EURCAD",
  "as_of_utc": "2026-11-16T09:00:00Z",
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
      "sha256": "721a7ee0e03d55b9755193631d4ca417dfe6d264b539c93a1cf4825e478f6b2e",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T06:01:12Z",
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
      "sha256": "04454423c8cacf930d0febb3f1bcb080c97f423e9e223a0f86e79b270e5e7845",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T09:01:15Z",
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
      "sha256": "2140f88b425fa3d259c9c1019c3fc7fff70b527258d2385d5fac13e38b62e698",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T09:01:14Z",
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
      "last_closed_bar_utc": "2026-11-16T06:00:00Z",
      "close": 1.57309,
      "ema": {
        "20": 1.576598729890948,
        "50": 1.5758765713696932,
        "200": 1.581428556370912
      },
      "ema20_change_5bars": -0.0022006809348509293,
      "atr14": 0.0026817444746074547,
      "trend": "NEUTRAL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T09:00:00Z",
      "close": 1.57413,
      "ema": {
        "20": 1.5735611125980171,
        "50": 1.5753832274238537,
        "200": 1.575742532974497
      },
      "ema20_change_5bars": -0.00025508046319533406,
      "atr14": 0.00116303892211002,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T09:00:00Z",
      "close": 1.57413,
      "ema": {
        "20": 1.573051462744697,
        "50": 1.5731702220651465,
        "200": 1.5754315124445446
      },
      "ema20_change_5bars": 9.279643649184877e-05,
      "atr14": 0.0006015456330165354,
      "trend": "NEUTRAL"
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
    "tick_time_utc": "2026-11-16T09:01:10Z",
    "bid": 1.5741100000000001,
    "ask": 1.5742500000000001,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 14.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -3e-12
  },
  "rtv": {
    "value": 1.518754423213022,
    "baseline_median": 706.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-16T09:00:00Z"
  }
}
```
