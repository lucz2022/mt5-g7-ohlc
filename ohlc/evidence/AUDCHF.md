# AUDCHF candidate evidence

JSON SHA-256: ab4f9f869334b6da0bcbafc116fa46e3bc57b22040454875a4404bb35c93f5a3

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "AUDCHF",
  "as_of_utc": "2026-11-16T20:30:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/AUDCHF/D1.json",
      "sha256": "24be80954fc9e2ded1034a63520481173b00b1fb9f5ad7a410030d4b1efb317e",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T02:49:54Z",
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
      "path": "ohlc/pairs/AUDCHF/H4.json",
      "sha256": "c8e3e0f6d9018c404b76dbfdfe28ff18b88dd565af6797bbcdfdd91006f20d91",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T18:01:12Z",
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
      "path": "ohlc/pairs/AUDCHF/H1.json",
      "sha256": "71b2f69beb3aa170a81b8cc3482fb474e8b3d8f7d7eaf9771735c586be4f353f",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T20:01:11Z",
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
      "path": "ohlc/pairs/AUDCHF/M15.json",
      "sha256": "89e51a284b4dcd244b08dc34eb32e3cb7f6785f2dd01f4213479893cebe7f217",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T20:31:12Z",
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
      "path": "ohlc/pairs/AUDCHF/W1.json",
      "sha256": "9e1254f4dcfdd18105539e9c0556bba062d2bbb4e5cf62fa7e849334c8cead17",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T02:50:22Z",
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
      "close": 0.56794,
      "ema": {
        "20": 0.5725696736974214,
        "50": 0.5751757814100582,
        "200": 0.5655402332871928
      },
      "ema20_change_5bars": -0.002783684919222096,
      "atr14": 0.005033843831566784,
      "trend": "SELL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-16T18:00:00Z",
      "close": 0.56632,
      "ema": {
        "20": 0.5678406640989785,
        "50": 0.5690092623250811,
        "200": 0.574281838714614
      },
      "ema20_change_5bars": -0.0006458144413795663,
      "atr14": 0.0018468279227931922,
      "trend": "SELL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T20:00:00Z",
      "close": 0.56613,
      "ema": {
        "20": 0.5669823400042813,
        "50": 0.5676221586185562,
        "200": 0.568969653619424
      },
      "ema20_change_5bars": -0.00043885321692083146,
      "atr14": 0.0009056136894142545,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-16T20:30:00Z",
      "close": 0.56588,
      "ema": {
        "20": 0.5661691303992545,
        "50": 0.566593079674134,
        "200": 0.5675942594299785
      },
      "ema20_change_5bars": -0.00014531389910565906,
      "atr14": 0.00038904306965871293,
      "trend": "SELL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-14T22:00:00Z",
      "close": 0.56794,
      "ema": {
        "20": 0.5721522347547874,
        "50": 0.5622993805930231,
        "200": 0.5799083356041983
      },
      "ema20_change_5bars": -1.708889271689884e-05,
      "atr14": 0.009567607327514573,
      "trend": "NEUTRAL"
    }
  },
  "candidates": [
    {
      "symbol": "AUDCHF",
      "enabled": 0,
      "direction": "SELL",
      "mode": "BREAKOUT",
      "zone_low": 0.56694,
      "zone_high": 0.56722,
      "invalidation": 0.56745,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.5,
      "factor_group": "CHF_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 1.1705,
      "pivot": {
        "side": "LOW",
        "level": 0.56708,
        "index": 981,
        "confirmed_index": 983,
        "pivot_utc": "2026-11-16T02:00:00Z",
        "confirmed_utc": "2026-11-16T04:00:00Z"
      },
      "breakout_close_utc": "2026-11-16T13:00:00Z",
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": true,
      "valid_until_utc": "2026-11-17T20:30:00Z"
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
    "broker_symbol": "AUDCHF",
    "tick_time_utc": "2026-11-16T20:31:07Z",
    "bid": 0.56585,
    "ask": 0.56596,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 11.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -5e-12
  },
  "rtv": {
    "value": 0.6187050359712231,
    "baseline_median": 764.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-16T20:30:00Z"
  }
}
```
