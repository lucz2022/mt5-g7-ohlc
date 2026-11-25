# EURUSD candidate evidence

JSON SHA-256: a891242acc5378924b0d077fbf701d99f4d36c0a8d7501139e455901d6c79e45

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "EURUSD",
  "as_of_utc": "2026-11-25T09:30:00Z",
  "price_basis": "BID",
  "status": "REJECT",
  "reasons": [
    "D1_H4_TREND_CONFLICT"
  ],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/EURUSD/D1.json",
      "sha256": "d8513b0e2c2841673192d9bcb87c58a4117b5df445e792303ebb8f384cf85751",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T22:01:08Z",
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
      "path": "ohlc/pairs/EURUSD/H4.json",
      "sha256": "64a397d6f431ffef5b6d23f472ea86cc8edac6472a8c9901f71720c3f1f46c8e",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-25T06:01:10Z",
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
      "path": "ohlc/pairs/EURUSD/H1.json",
      "sha256": "4738c2a87a596689dc8fc79ff2bfeb8263494555537f4b27072ccef81ff24b9d",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-25T09:01:09Z",
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
      "path": "ohlc/pairs/EURUSD/M15.json",
      "sha256": "164d6df40f00eec708994942229dfc44129e579c137a3c79befa79017e0b2d18",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-25T09:31:08Z",
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
      "path": "ohlc/pairs/EURUSD/W1.json",
      "sha256": "c536aa181fdb94de842cbad195bee9f2ee50d6697d6f3ef7ff5d68642b641f36",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T03:31:07Z",
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
      "close": 1.09651,
      "ema": {
        "20": 1.1063709893941425,
        "50": 1.119310870478042,
        "200": 1.141025981113017
      },
      "ema20_change_5bars": -0.007173466290224972,
      "atr14": 0.006865517934509576,
      "trend": "SELL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-25T06:00:00Z",
      "close": 1.09409,
      "ema": {
        "20": 1.0955173011874588,
        "50": 1.0993169200499286,
        "200": 1.113453692978826
      },
      "ema20_change_5bars": 0.00026327435048578707,
      "atr14": 0.002622056112470765,
      "trend": "NEUTRAL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-25T09:00:00Z",
      "close": 1.0943,
      "ema": {
        "20": 1.0948239534451196,
        "50": 1.0948465896495412,
        "200": 1.0991742824184398
      },
      "ema20_change_5bars": -0.0005508730174601517,
      "atr14": 0.000981860628993299,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-25T09:30:00Z",
      "close": 1.09339,
      "ema": {
        "20": 1.094094412819751,
        "50": 1.0947053701236895,
        "200": 1.0948283699814823
      },
      "ema20_change_5bars": -7.262408449171254e-05,
      "atr14": 0.0006043447895852992,
      "trend": "SELL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-21T22:00:00Z",
      "close": 1.09653,
      "ema": {
        "20": 1.1313730312189925,
        "50": 1.1431349861403015,
        "200": 1.1264673937408674
      },
      "ema20_change_5bars": -0.01487055574361218,
      "atr14": 0.013123070373261266,
      "trend": "SELL"
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
    "broker_symbol": "EURUSD",
    "tick_time_utc": "2026-11-25T09:31:07Z",
    "bid": 1.09352,
    "ask": 1.09361,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 9.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": 8e-12
  },
  "rtv": {
    "value": 1.823960880195599,
    "baseline_median": 613.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-25T09:30:00Z"
  }
}
```
