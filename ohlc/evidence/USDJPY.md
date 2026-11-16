# USDJPY candidate evidence

JSON SHA-256: 31e4c0c89313a6bbdeb775c4d362135bb3de559ad9ba2780f5eb95137a68119a

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "USDJPY",
  "as_of_utc": "2026-11-16T22:00:00Z",
  "price_basis": "BID",
  "status": "REJECT",
  "reasons": [
    "D1_H4_TREND_CONFLICT"
  ],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/USDJPY/D1.json",
      "sha256": "570a43fade17363c7e8fc3547997032ef33960f37be0bcaf32ead834795673b8",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T22:01:12Z",
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
      "path": "ohlc/pairs/USDJPY/H4.json",
      "sha256": "4afac750f6cfc5ef012a4318e2fafa3b402cd27f21912c465e0785dc7096cbe8",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T22:01:12Z",
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
      "path": "ohlc/pairs/USDJPY/H1.json",
      "sha256": "7ddf61bbdeb87605c37bcaa75ca5ff67ab031605cfe7b0df62dd05d534300f4d",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T22:01:12Z",
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
      "path": "ohlc/pairs/USDJPY/M15.json",
      "sha256": "0d2509b4170db50a3ff567c8120064d0190293e385d110b59c1ab8bf42e51533",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T22:01:12Z",
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
      "path": "ohlc/pairs/USDJPY/W1.json",
      "sha256": "2d356cd5f619b7870c634390d2ceb63dd5f50314f01b8cc8903246cc629fcc98",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T02:33:03Z",
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
      "last_closed_bar_utc": "2026-11-16T22:00:00Z",
      "close": 159.419,
      "ema": {
        "20": 158.55531902994306,
        "50": 158.25827389570438,
        "200": 157.88069846772743
      },
      "ema20_change_5bars": 0.6249761520898289,
      "atr14": 0.9097469839372073,
      "trend": "BUY"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-16T22:00:00Z",
      "close": 159.419,
      "ema": {
        "20": 159.5161402926583,
        "50": 159.04406591830033,
        "200": 158.27023309141813
      },
      "ema20_change_5bars": -0.0013517282124553276,
      "atr14": 0.31972548859276456,
      "trend": "NEUTRAL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T22:00:00Z",
      "close": 159.419,
      "ema": {
        "20": 159.56493462963942,
        "50": 159.61479948169514,
        "200": 159.03862331753334
      },
      "ema20_change_5bars": -0.06357991030623111,
      "atr14": 0.1601601796042511,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T22:00:00Z",
      "close": 159.419,
      "ema": {
        "20": 159.4752690094447,
        "50": 159.52080106940602,
        "200": 159.61091103701966
      },
      "ema20_change_5bars": -0.015447802258705678,
      "atr14": 0.06328081670925047,
      "trend": "SELL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-14T22:00:00Z",
      "close": 159.666,
      "ema": {
        "20": 158.2803507432631,
        "50": 157.2459979431644,
        "200": 147.22575514765515
      },
      "ema20_change_5bars": -0.04434810719143911,
      "atr14": 2.3506444471435506,
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
    "broker_symbol": "USDJPY",
    "tick_time_utc": "2026-11-16T22:01:02Z",
    "bid": 159.447,
    "ask": 159.518,
    "digits": 3,
    "point": 0.001,
    "spread_points": 71.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": 2e-12
  },
  "rtv": {
    "value": 0.32734806629834257,
    "baseline_median": 724.0,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-16T22:00:00Z"
  }
}
```
