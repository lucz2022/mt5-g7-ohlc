# EURCAD candidate evidence

JSON SHA-256: 96f602a04fa0eea1d9c0d11552c6595e864f9044908fdf0db78c8ac0654bf109

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "EURCAD",
  "as_of_utc": "2026-11-16T11:30:00Z",
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
      "sha256": "26be111ef83067b8a5fb3f97275fecae94a3d413442725468871d0c105e90c0e",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T10:01:11Z",
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
      "sha256": "408d4e6c5c9185a3d21905d2772a01cbe4c9a1dfffe12ae2093736ef899deaa1",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T11:01:10Z",
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
      "sha256": "8cc18041156399e5347928b249080f68cbc150641521154aa34b96c53f5e4167",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURCAD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T11:31:12Z",
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
      "last_closed_bar_utc": "2026-11-16T10:00:00Z",
      "close": 1.57273,
      "ema": {
        "20": 1.5762302794251435,
        "50": 1.5757531764108355,
        "200": 1.5813433252981288
      },
      "ema20_change_5bars": -0.002137758941055612,
      "atr14": 0.0026923341549926283,
      "trend": "NEUTRAL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T11:00:00Z",
      "close": 1.57205,
      "ema": {
        "20": 1.5733455819679913,
        "50": 1.5751525448076404,
        "200": 1.5756761240691435
      },
      "ema20_change_5bars": -0.00034146042452043446,
      "atr14": 0.001243385601207081,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T11:30:00Z",
      "close": 1.5721699999999998,
      "ema": {
        "20": 1.5727606936921639,
        "50": 1.573010887742074,
        "200": 1.5751751595708179
      },
      "ema20_change_5bars": -0.0003390115332166932,
      "atr14": 0.0006378547338692944,
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
    "tick_time_utc": "2026-11-16T11:31:08Z",
    "bid": 1.57205,
    "ask": 1.57216,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 11.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -5e-12
  },
  "rtv": {
    "value": 0.8240794856808884,
    "baseline_median": 855.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-16T11:30:00Z"
  }
}
```
