# EURCAD candidate evidence

JSON SHA-256: 53e41843c890771ef7b79af75560184b099fceca941285a6e35d5047055e561d

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "EURCAD",
  "as_of_utc": "2026-11-16T18:00:00Z",
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
      "sha256": "e420ffa52097c816b1c69757a2fcf11758d781b8f7c4fa897064567fd2d04152",
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
    "M15": {
      "path": "ohlc/pairs/EURCAD/M15.json",
      "sha256": "3dd50454266d78fa536fce9d556ca4e32b043351ab60c001c4e98c7a93803851",
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
      "last_closed_bar_utc": "2026-11-16T18:00:00Z",
      "close": 1.57325,
      "ema": {
        "20": 1.573568312128002,
        "50": 1.5748168772399196,
        "200": 1.5755473658918506
      },
      "ema20_change_5bars": 0.00024156589116541838,
      "atr14": 0.0013441984772168845,
      "trend": "NEUTRAL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T18:00:00Z",
      "close": 1.57325,
      "ema": {
        "20": 1.5738186412467845,
        "50": 1.5735544110930932,
        "200": 1.574857261348904
      },
      "ema20_change_5bars": -0.00017822320598326336,
      "atr14": 0.0007847528467810186,
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
    "tick_time_utc": "2026-11-16T18:01:07Z",
    "bid": 1.57321,
    "ask": 1.57333,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 12.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": 1e-11
  },
  "rtv": {
    "value": 0.7411513859275053,
    "baseline_median": 1172.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-16T18:00:00Z"
  }
}
```
