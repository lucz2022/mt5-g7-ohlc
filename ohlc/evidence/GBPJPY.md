# GBPJPY candidate evidence

JSON SHA-256: 6ae8d8d0f8a8147c1ea127a1e16184953db64c21407e16945c712120ebb90844

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "GBPJPY",
  "as_of_utc": "2026-11-16T23:30:00Z",
  "price_basis": "BID",
  "status": "REJECT",
  "reasons": [
    "D1_H4_TREND_CONFLICT"
  ],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/GBPJPY/D1.json",
      "sha256": "a7e498255cb0d11be6df19baeee91a8e597a7995292de0f01b91d0cd4fa6d06c",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T22:01:16Z",
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
      "sha256": "9b4ff7fc0d3abd3c4b05ed231fded653a011ee7d6d7a88b78bd47395215b0f3e",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T22:01:16Z",
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
      "sha256": "aed04eec826c6d822ba969f8001b3015e96ce582fb3d9bd198c62ba2f8c33c0f",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T23:01:11Z",
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
      "sha256": "840c0c34a615a8c5a76e3fb9bfb6bbb6fcfa0da7e6ece77b961832d86fdba1a5",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T23:31:10Z",
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
      "sha256": "333df27f255c29b8165cf55d1a0ee0141a8493a250e94b5c61fcf4be68fda1d0",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-16T02:33:14Z",
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
      "close": 210.192,
      "ema": {
        "20": 211.20227859616742,
        "50": 211.2147018197506,
        "200": 211.20495889302828
      },
      "ema20_change_5bars": 0.02691140249467594,
      "atr14": 1.247404542259722,
      "trend": "NEUTRAL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-16T22:00:00Z",
      "close": 210.192,
      "ema": {
        "20": 211.15968657296085,
        "50": 211.51784298562438,
        "200": 211.11837021573928
      },
      "ema20_change_5bars": -0.45859910879738663,
      "atr14": 0.4511741533938376,
      "trend": "SELL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T23:00:00Z",
      "close": 210.184,
      "ema": {
        "20": 210.50454067952924,
        "50": 210.9117030646347,
        "200": 211.51708828859537
      },
      "ema20_change_5bars": -0.1868647536969945,
      "atr14": 0.19817037417760877,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T23:30:00Z",
      "close": 210.237,
      "ema": {
        "20": 210.24740043013304,
        "50": 210.37674651174956,
        "200": 210.9087394369241
      },
      "ema20_change_5bars": -0.020734355312470143,
      "atr14": 0.08141087471027945,
      "trend": "SELL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-14T22:00:00Z",
      "close": 210.943,
      "ema": {
        "20": 211.5866403945146,
        "50": 210.25198174576218,
        "200": 193.34176149105568
      },
      "ema20_change_5bars": -0.5138697724364931,
      "atr14": 2.9537752122945373,
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
    "tick_time_utc": "2026-11-16T23:31:08Z",
    "bid": 210.231,
    "ask": 210.25,
    "digits": 3,
    "point": 0.001,
    "spread_points": 19.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -5e-12
  },
  "rtv": {
    "value": 0.46599645180366644,
    "baseline_median": 845.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-16T23:30:00Z"
  }
}
```
