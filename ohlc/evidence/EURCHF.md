# EURCHF candidate evidence

JSON SHA-256: 73dc3ae5bc4edfd687831aa05115ecd10ba76b966426f1f39e7e3bb23d7df7a8

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "EURCHF",
  "as_of_utc": "2026-11-16T13:15:00Z",
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
      "sha256": "a1e9206af51497bcef9d99ba39bd2206b1f67fbc831be594a423dede93ffe3d6",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURCHF",
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
      "path": "ohlc/pairs/EURCHF/H1.json",
      "sha256": "db581ce9b81f318b41f0e12977fd918d571e6cff824f674c2814664eb9afacf7",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T13:01:14Z",
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
      "sha256": "bb724eaf622b5df21b428b8f146150e65257507acf6b5990153b9ef1de63299a",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T13:16:13Z",
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
      "last_closed_bar_utc": "2026-11-16T10:00:00Z",
      "close": 0.92524,
      "ema": {
        "20": 0.9236622807294224,
        "50": 0.9218286458022682,
        "200": 0.9256473362742753
      },
      "ema20_change_5bars": 0.0007827002484662726,
      "atr14": 0.0019089664154203494,
      "trend": "BUY"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T13:00:00Z",
      "close": 0.92417,
      "ema": {
        "20": 0.9247880272121066,
        "50": 0.9243408634418371,
        "200": 0.9217951192283205
      },
      "ema20_change_5bars": 8.817041115005697e-05,
      "atr14": 0.0008316770663700709,
      "trend": "NEUTRAL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T13:15:00Z",
      "close": 0.92427,
      "ema": {
        "20": 0.9246488888033308,
        "50": 0.9247418937272275,
        "200": 0.9243266584520327
      },
      "ema20_change_5bars": -0.0003153533011135412,
      "atr14": 0.0003879432377231331,
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
    "tick_time_utc": "2026-11-16T13:16:10Z",
    "bid": 0.92427,
    "ask": 0.9244,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 13.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": 4e-12
  },
  "rtv": {
    "value": 1.152542372881356,
    "baseline_median": 649.0,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-16T13:15:00Z"
  }
}
```
