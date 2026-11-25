# AUDUSD candidate evidence

JSON SHA-256: cbec9851d70be856c9cac903691a9843bdd1e0bcbf54de3b8d310794671cd811

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "AUDUSD",
  "as_of_utc": "2026-11-25T09:00:00Z",
  "price_basis": "BID",
  "status": "WATCH",
  "reasons": [
    "NO_VALID_NEARBY_ZONE"
  ],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/AUDUSD/D1.json",
      "sha256": "0ae9250a53c545fbd4b038238217ec7b20a0ed439411270fc57580b420605f9c",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T22:01:26Z",
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
      "path": "ohlc/pairs/AUDUSD/H4.json",
      "sha256": "bec3306d1642bd70f6adce87eb1cee15c6908d3ec986d06124863c22a5d7b877",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-25T06:01:11Z",
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
      "path": "ohlc/pairs/AUDUSD/H1.json",
      "sha256": "d0a16a209cff9eaf3451e4c32eaff43a970bdd34846c5269af080fc492fe528e",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-25T09:01:10Z",
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
      "path": "ohlc/pairs/AUDUSD/M15.json",
      "sha256": "38ba87e1d47a9ad4af2fb91f97e47785b23bcc1726777f52ca3f6e5cc4aaba69",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-25T09:01:10Z",
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
      "path": "ohlc/pairs/AUDUSD/W1.json",
      "sha256": "b08f8af0a485d80a230c14d8e3ad17179e342f4caf71a4037de1e4c3d98e91f6",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T03:31:08Z",
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
      "close": 0.664,
      "ema": {
        "20": 0.679624336510056,
        "50": 0.6908809092847834,
        "200": 0.6952376207096741
      },
      "ema20_change_5bars": -0.0096590476862366,
      "atr14": 0.005319249581974272,
      "trend": "SELL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-25T06:00:00Z",
      "close": 0.65897,
      "ema": {
        "20": 0.664334192906287,
        "50": 0.6700008210920051,
        "200": 0.686478312902902
      },
      "ema20_change_5bars": -0.0010356989287162444,
      "atr14": 0.0026660925306413114,
      "trend": "SELL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-25T09:00:00Z",
      "close": 0.65735,
      "ema": {
        "20": 0.6611442296755649,
        "50": 0.6627140306271182,
        "200": 0.6697834186086618
      },
      "ema20_change_5bars": -0.0021594337652764972,
      "atr14": 0.0014986010473380424,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-25T09:00:00Z",
      "close": 0.65735,
      "ema": {
        "20": 0.6583558029745077,
        "50": 0.6603717402434548,
        "200": 0.6627982116230158
      },
      "ema20_change_5bars": -0.0007982621351626529,
      "atr14": 0.0007548821388608389,
      "trend": "SELL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-21T22:00:00Z",
      "close": 0.66159,
      "ema": {
        "20": 0.6961727865250014,
        "50": 0.6927604783399396,
        "200": 0.6824584103468689
      },
      "ema20_change_5bars": -0.007863296846279177,
      "atr14": 0.011691639324891808,
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
    "broker_symbol": "AUDUSD",
    "tick_time_utc": "2026-11-25T09:01:08Z",
    "bid": 0.65738,
    "ask": 0.65747,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 9.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -3e-12
  },
  "rtv": {
    "value": 1.1407657657657657,
    "baseline_median": 888.0,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-25T09:00:00Z"
  }
}
```
