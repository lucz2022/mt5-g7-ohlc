# USDJPY candidate evidence

JSON SHA-256: 200fd2317f8b96cd19bf78260aac0bc6edc7e01121f9fdfebd797c2af63e33d9

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "USDJPY",
  "as_of_utc": "2026-11-25T12:45:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/USDJPY/D1.json",
      "sha256": "4c1c6889ae7d5420c5d3a77fd6f2a2bf1ff6bd53e612e829bb4aec1de4552a39",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-24T22:01:15Z",
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
      "sha256": "2989fcf5cad10c8bdbd5ee8262c820efd93b14c9e98380f1a4a774be01be5176",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-25T10:01:09Z",
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
      "sha256": "719b309cd9744aced7df901dee16b67239318098c651fd1b415adb2974893240",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-25T12:31:08Z",
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
      "sha256": "f42ffcbdc82d18dc18f93fa81918962297a66b5c6c88bff43462fc0e47255b41",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-25T12:46:09Z",
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
      "sha256": "0daf268f91764c0cb7aa8f3c1c5d08ae1348db1f724ddf622a1f5d47ae0c0c69",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "USDJPY",
      "digits": 3,
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
      "close": 159.247,
      "ema": {
        "20": 158.83265740062717,
        "50": 158.4555281097186,
        "200": 157.9495776116681
      },
      "ema20_change_5bars": 0.19965446877392878,
      "atr14": 0.9013335498749152,
      "trend": "BUY"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-25T10:00:00Z",
      "close": 159.447,
      "ema": {
        "20": 159.231597190289,
        "50": 159.18874948177472,
        "200": 158.58026801784015
      },
      "ema20_change_5bars": 0.06428632813987178,
      "atr14": 0.35852377648091477,
      "trend": "BUY"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-25T12:00:00Z",
      "close": 159.296,
      "ema": {
        "20": 159.28826072606594,
        "50": 159.22132458493755,
        "200": 159.18677400987156
      },
      "ema20_change_5bars": 0.03824955139697295,
      "atr14": 0.17719527788936518,
      "trend": "BUY"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-25T12:45:00Z",
      "close": 159.283,
      "ema": {
        "20": 159.31319871537042,
        "50": 159.30353279434897,
        "200": 159.22032084000082
      },
      "ema20_change_5bars": -0.021070634378162367,
      "atr14": 0.09387108182771578,
      "trend": "NEUTRAL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-21T22:00:00Z",
      "close": 158.556,
      "ema": {
        "20": 158.30660305342863,
        "50": 157.29737198336252,
        "200": 147.350222460138
      },
      "ema20_change_5bars": 0.01673266492198877,
      "atr14": 2.293741272331575,
      "trend": "BUY"
    }
  },
  "candidates": [
    {
      "symbol": "USDJPY",
      "enabled": 0,
      "direction": "BUY",
      "mode": "PULLBACK",
      "zone_low": 159.079,
      "zone_high": 159.133,
      "invalidation": 159.035,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.75,
      "factor_group": "USD_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 0.8465,
      "pivot": {
        "side": "LOW",
        "level": 159.106,
        "index": 991,
        "confirmed_index": 993,
        "pivot_utc": "2026-11-25T04:00:00Z",
        "confirmed_utc": "2026-11-25T06:00:00Z"
      },
      "breakout_close_utc": null,
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": false,
      "valid_until_utc": "2026-11-26T12:45:00Z"
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
    "broker_symbol": "USDJPY",
    "tick_time_utc": "2026-11-25T12:46:08Z",
    "bid": 159.278,
    "ask": 159.287,
    "digits": 3,
    "point": 0.001,
    "spread_points": 9.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -1.5e-11
  },
  "rtv": {
    "value": 1.0483333333333333,
    "baseline_median": 1200.0,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-25T12:45:00Z"
  }
}
```
