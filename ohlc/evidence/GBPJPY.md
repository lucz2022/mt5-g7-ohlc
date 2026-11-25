# GBPJPY candidate evidence

JSON SHA-256: ddbc3984c9627a0dadc6fcc94a33b2b1336a4e8ac999ecb9319be0483bd2169e

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "GBPJPY",
  "as_of_utc": "2026-11-25T07:30:00Z",
  "price_basis": "BID",
  "status": "REJECT",
  "reasons": [
    "D1_H4_TREND_CONFLICT"
  ],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/GBPJPY/D1.json",
      "sha256": "add83b4b2b668651031043ba6faa38196963d86bc2b3fc22b6384d78e0bf9873",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-24T22:01:29Z",
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
      "sha256": "bd26f16459bb828a9358fb3630fe707e70ebf402f75bfb73d06387c857664687",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-25T06:01:12Z",
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
      "sha256": "6069db5c7d24b7ac2961e2c99922d98051c7d2d8909424a03dc99fee96105e32",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-25T07:01:10Z",
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
      "sha256": "4ad57135775c59b1f062d5a0fc290e749762f9e07b78c10f0ef790c64efbd369",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-25T07:31:15Z",
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
      "last_closed_bar_utc": "2026-11-24T22:00:00Z",
      "close": 208.842,
      "ema": {
        "20": 210.02467443684597,
        "50": 210.67177829024365,
        "200": 211.05242979297807
      },
      "ema20_change_5bars": -1.1080538168293117,
      "atr14": 1.4416563023564941,
      "trend": "SELL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-25T06:00:00Z",
      "close": 208.588,
      "ema": {
        "20": 208.50914211351497,
        "50": 209.312448711502,
        "200": 210.4397528471081
      },
      "ema20_change_5bars": 0.12428794857703451,
      "atr14": 0.589217843205865,
      "trend": "NEUTRAL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-25T07:00:00Z",
      "close": 208.331,
      "ema": {
        "20": 208.52432503117367,
        "50": 208.36955399401234,
        "200": 209.30969182041372
      },
      "ema20_change_5bars": -0.012240720899029611,
      "atr14": 0.25451287327028504,
      "trend": "NEUTRAL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-25T07:30:00Z",
      "close": 208.059,
      "ema": {
        "20": 208.51407752340248,
        "50": 208.58971786123172,
        "200": 208.370622767599
      },
      "ema20_change_5bars": -0.12595950961019753,
      "atr14": 0.1456587612251377,
      "trend": "SELL"
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
    "broker_symbol": "GBPJPY",
    "tick_time_utc": "2026-11-25T07:31:13Z",
    "bid": 208.072,
    "ask": 208.09,
    "digits": 3,
    "point": 0.001,
    "spread_points": 18.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -1e-12
  },
  "rtv": {
    "value": 1.5135344160866202,
    "baseline_median": 1293.0,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-25T07:30:00Z"
  }
}
```
