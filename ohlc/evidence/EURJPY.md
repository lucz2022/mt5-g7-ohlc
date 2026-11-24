# EURJPY candidate evidence

JSON SHA-256: b9cb793245231fb51ef8c2bd9409d048630cb86d7f2945d734a291ac4f520987

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "EURJPY",
  "as_of_utc": "2026-11-24T18:00:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/EURJPY/D1.json",
      "sha256": "638a8af9549a53dd62cc7e4a080a1402c492316c5c519fea7bfac8c12f983e54",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURJPY",
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
    },
    "H4": {
      "path": "ohlc/pairs/EURJPY/H4.json",
      "sha256": "0d7ff92c4d96e5b94e046b903d4dcc5611bbec282b9247125104b5fa66a604a4",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-24T18:01:13Z",
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
      "path": "ohlc/pairs/EURJPY/H1.json",
      "sha256": "a91d177d6a3b1564344bc8ec69c01703fe9b1cf0583c6588b829843d0853456c",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-24T18:01:13Z",
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
      "path": "ohlc/pairs/EURJPY/M15.json",
      "sha256": "d79bfc4e39c5e05f9e98e5f70f17cbf6834d2a2275c60078bfc3e111ee1dcf9f",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-24T18:01:13Z",
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
      "path": "ohlc/pairs/EURJPY/W1.json",
      "sha256": "8eab442550f84a641719f42bcd7f6ffe0d7fe97be51cc05f732d70b8926fc22c",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURJPY",
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
      "last_closed_bar_utc": "2026-11-23T22:00:00Z",
      "close": 173.331,
      "ema": {
        "20": 175.84349002410806,
        "50": 177.46578566113328,
        "200": 180.27363518368958
      },
      "ema20_change_5bars": -0.9393252070073856,
      "atr14": 1.1817125338410284,
      "trend": "SELL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-24T18:00:00Z",
      "close": 174.709,
      "ema": {
        "20": 174.38330862179544,
        "50": 175.04698786424015,
        "200": 176.61286354728185
      },
      "ema20_change_5bars": -0.12098717881002585,
      "atr14": 0.5399787937287043,
      "trend": "SELL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-24T18:00:00Z",
      "close": 174.709,
      "ema": {
        "20": 174.1966373552539,
        "50": 174.18687817663556,
        "200": 175.04943815923258
      },
      "ema20_change_5bars": 0.26490608230002977,
      "atr14": 0.26402603280655607,
      "trend": "BUY"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-24T18:00:00Z",
      "close": 174.709,
      "ema": {
        "20": 174.56399414989383,
        "50": 174.31027852866728,
        "200": 174.17325076735054
      },
      "ema20_change_5bars": 0.06135081310657142,
      "atr14": 0.12375024226299901,
      "trend": "BUY"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-21T22:00:00Z",
      "close": 173.878,
      "ema": {
        "20": 179.10172671931758,
        "50": 179.80484381829976,
        "200": 165.9832397052049
      },
      "ema20_change_5bars": -2.3316194328724293,
      "atr14": 2.4774870993911042,
      "trend": "SELL"
    }
  },
  "candidates": [
    {
      "symbol": "EURJPY",
      "enabled": 0,
      "direction": "SELL",
      "mode": "PULLBACK",
      "zone_low": 174.778,
      "zone_high": 174.858,
      "invalidation": 174.924,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.5,
      "factor_group": "JPY_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 0.2613,
      "pivot": {
        "side": "HIGH",
        "level": 174.818,
        "index": 996,
        "confirmed_index": 998,
        "pivot_utc": "2026-11-24T15:00:00Z",
        "confirmed_utc": "2026-11-24T17:00:00Z"
      },
      "breakout_close_utc": null,
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": false,
      "valid_until_utc": "2026-11-25T18:00:00Z"
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
    "broker_symbol": "EURJPY",
    "tick_time_utc": "2026-11-24T18:01:11Z",
    "bid": 174.715,
    "ask": 174.726,
    "digits": 3,
    "point": 0.001,
    "spread_points": 11.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": 4e-12
  },
  "rtv": {
    "value": 0.6144007579346281,
    "baseline_median": 2111.0,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-24T18:00:00Z"
  }
}
```
