# EURCHF candidate evidence

JSON SHA-256: bb20b37c35f1423d6ed3835503dbe28826195a31f9a06e1380d1b9243bf3b950

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "EURCHF",
  "as_of_utc": "2026-11-16T16:30:00Z",
  "price_basis": "BID",
  "status": "REJECT",
  "reasons": [
    "D1_H4_TREND_CONFLICT"
  ],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/EURCHF/D1.json",
      "sha256": "ef9974942bdc205073c3fbd0496d11d3cad78402b8bb72762ddde69cbcb1ad59",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T02:38:24Z",
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
      "path": "ohlc/pairs/EURCHF/H4.json",
      "sha256": "87d14156d4b45bc79bff344c2f9e590d766a50a224f2745f23b9a544960a8eca",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T14:01:12Z",
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
      "path": "ohlc/pairs/EURCHF/H1.json",
      "sha256": "0f8e4c5db123df424f129344a42162f37020ec24284b3eb7ff60f6fdb819536b",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T16:01:13Z",
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
      "path": "ohlc/pairs/EURCHF/M15.json",
      "sha256": "1e6431881a411a06a7a757063e97920fba3378881bd1eb36e13950297528bec6",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T16:31:15Z",
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
      "path": "ohlc/pairs/EURCHF/W1.json",
      "sha256": "3bd1176e25e90e642fbf8b69a230e48dd48cac6a1f6b0737702850b341292fd9",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T02:35:37Z",
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
      "close": 0.92454,
      "ema": {
        "20": 0.9228921086223958,
        "50": 0.9276764277470319,
        "200": 0.9278971815846238
      },
      "ema20_change_5bars": -5.635728176855981e-05,
      "atr14": 0.0053609001242376515,
      "trend": "SELL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-16T14:00:00Z",
      "close": 0.92443,
      "ema": {
        "20": 0.9237353968504297,
        "50": 0.9219306596927337,
        "200": 0.9256359466455766
      },
      "ema20_change_5bars": 0.000580538320040902,
      "atr14": 0.001900468814318893,
      "trend": "BUY"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T16:00:00Z",
      "close": 0.92351,
      "ema": {
        "20": 0.9245480918526984,
        "50": 0.9242888681055453,
        "200": 0.9218570129354147
      },
      "ema20_change_5bars": -0.00026952587732664846,
      "atr14": 0.0008573631613757406,
      "trend": "NEUTRAL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T16:30:00Z",
      "close": 0.92409,
      "ema": {
        "20": 0.9240432947807637,
        "50": 0.9243913183932669,
        "200": 0.9242760848950653
      },
      "ema20_change_5bars": -0.00028882404704233533,
      "atr14": 0.0005032498677318791,
      "trend": "SELL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-14T22:00:00Z",
      "close": 0.92454,
      "ema": {
        "20": 0.9279469187548538,
        "50": 0.9275518604841541,
        "200": 0.9551494912007126
      },
      "ema20_change_5bars": -0.0041139979910505,
      "atr14": 0.010020752886545007,
      "trend": "NEUTRAL"
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
    "broker_symbol": "EURCHF",
    "tick_time_utc": "2026-11-16T16:31:04Z",
    "bid": 0.92387,
    "ask": 0.924,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 13.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -7e-12
  },
  "rtv": {
    "value": 0.8718882817243473,
    "baseline_median": 823.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-16T16:30:00Z"
  }
}
```
