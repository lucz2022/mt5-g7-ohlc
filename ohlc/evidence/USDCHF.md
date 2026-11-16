# USDCHF candidate evidence

JSON SHA-256: e395056b7d107f6666b7f6d66696914075935dde88c13be428a255c2617a1e5c

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "USDCHF",
  "as_of_utc": "2026-11-16T23:00:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/USDCHF/D1.json",
      "sha256": "cb0a6e2871dfa97950dd779c6fb055f41c22c48dc4e8eb3a903059f128adfa10",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T22:01:13Z",
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
      "path": "ohlc/pairs/USDCHF/H4.json",
      "sha256": "e019e62032c75b8017181d94861719aba9680a4cc9841f5f35572315a4d255bb",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T22:01:13Z",
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
      "path": "ohlc/pairs/USDCHF/H1.json",
      "sha256": "81f02191761c2299059589cf65c90aa91d86b87fcfff936851861eb9c469bde7",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDCHF",
      "digits": 5,
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
      "path": "ohlc/pairs/USDCHF/M15.json",
      "sha256": "50ffed10adbcb4aa1a74e46fe1100c52a4fc325964725a3c66f097a26ace2e47",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDCHF",
      "digits": 5,
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
    "W1": {
      "path": "ohlc/pairs/USDCHF/W1.json",
      "sha256": "1c53bb4427b1804806675a995580b07039d5f6814eb08b314f7b05c654bcec12",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T02:33:06Z",
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
      "close": 0.84007,
      "ema": {
        "20": 0.8278512358305994,
        "50": 0.8241383236817064,
        "200": 0.8116257467941371
      },
      "ema20_change_5bars": 0.004771070131656563,
      "atr14": 0.005847639510003899,
      "trend": "BUY"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-16T22:00:00Z",
      "close": 0.84007,
      "ema": {
        "20": 0.8358573044528845,
        "50": 0.830192005561112,
        "200": 0.8257585590388518
      },
      "ema20_change_5bars": 0.002454246354912648,
      "atr14": 0.002101084522539752,
      "trend": "BUY"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T23:00:00Z",
      "close": 0.83923,
      "ema": {
        "20": 0.8394806298757873,
        "50": 0.8378624976074306,
        "200": 0.8301062549650222
      },
      "ema20_change_5bars": 0.00024231329945789692,
      "atr14": 0.0010109504649507728,
      "trend": "BUY"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T23:00:00Z",
      "close": 0.83923,
      "ema": {
        "20": 0.8396925229871696,
        "50": 0.8396070482420189,
        "200": 0.8378104810559461
      },
      "ema20_change_5bars": -0.00019183538639389042,
      "atr14": 0.00040086100751699557,
      "trend": "NEUTRAL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-14T22:00:00Z",
      "close": 0.83881,
      "ema": {
        "20": 0.8177293760771989,
        "50": 0.8104723925673032,
        "200": 0.8493852612108518
      },
      "ema20_change_5bars": 0.00614406048752969,
      "atr14": 0.012704237441014843,
      "trend": "BUY"
    }
  },
  "candidates": [
    {
      "symbol": "USDCHF",
      "enabled": 0,
      "direction": "BUY",
      "mode": "PULLBACK",
      "zone_low": 0.83849,
      "zone_high": 0.83879,
      "invalidation": 0.83824,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.75,
      "factor_group": "USD_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 0.4352,
      "pivot": {
        "side": "LOW",
        "level": 0.83864,
        "index": 989,
        "confirmed_index": 991,
        "pivot_utc": "2026-11-16T13:00:00Z",
        "confirmed_utc": "2026-11-16T15:00:00Z"
      },
      "breakout_close_utc": null,
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": false,
      "valid_until_utc": "2026-11-17T23:00:00Z"
    }
  ],
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
    "broker_symbol": "USDCHF",
    "tick_time_utc": "2026-11-16T23:01:02Z",
    "bid": 0.83977,
    "ask": 0.84018,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 41.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -2e-12
  },
  "rtv": {
    "value": 0.2617124394184168,
    "baseline_median": 309.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-16T23:00:00Z"
  }
}
```
