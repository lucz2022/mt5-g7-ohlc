# EURJPY candidate evidence

JSON SHA-256: cf4ba8a118106fc3d0f4b8b4998711c231f5144ce1858c87d4f03b6bcb6a53fd

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "EURJPY",
  "as_of_utc": "2026-11-24T22:45:00Z",
  "price_basis": "BID",
  "status": "REJECT",
  "reasons": [
    "D1_H4_TREND_CONFLICT"
  ],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/EURJPY/D1.json",
      "sha256": "4d56d60ebccf2a2383a06a497cc8434dea25dbeff1bb0ec762d76372a628962e",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURJPY",
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
      "path": "ohlc/pairs/EURJPY/H4.json",
      "sha256": "750046f34725ec44dba0faad3be5ab7412c8008f1c1f4851f83d2aa609c0177b",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURJPY",
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
    "H1": {
      "path": "ohlc/pairs/EURJPY/H1.json",
      "sha256": "72ab00146d35f5f476526dc78eee1d7ebd708ab77a451a3a18de1eb36242db03",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURJPY",
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
    "M15": {
      "path": "ohlc/pairs/EURJPY/M15.json",
      "sha256": "df43000de0d4aed44ddbb7d4802454a74d28c2d2eb207cb19ea60e733bd12d4a",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "EURJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-24T22:46:09Z",
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
      "last_closed_bar_utc": "2026-11-24T22:00:00Z",
      "close": 174.618,
      "ema": {
        "20": 175.72677668847874,
        "50": 177.35410779351616,
        "200": 180.21630274345776
      },
      "ema20_change_5bars": -0.9135799491971568,
      "atr14": 1.2215902099952414,
      "trend": "SELL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-24T22:00:00Z",
      "close": 174.618,
      "ema": {
        "20": 174.40566018162446,
        "50": 175.03016480903997,
        "200": 176.59299006711913
      },
      "ema20_change_5bars": 0.013868742981429705,
      "atr14": 0.5160517370337956,
      "trend": "NEUTRAL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-24T22:00:00Z",
      "close": 174.618,
      "ema": {
        "20": 174.33659898280058,
        "50": 174.25117436267553,
        "200": 175.03267667927057
      },
      "ema20_change_5bars": 0.19389453751995234,
      "atr14": 0.21780519895324965,
      "trend": "BUY"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-24T22:45:00Z",
      "close": 174.603,
      "ema": {
        "20": 174.60033470516734,
        "50": 174.47328752876632,
        "200": 174.25095755737632
      },
      "ema20_change_5bars": -0.008657389134469895,
      "atr14": 0.07649536247237573,
      "trend": "NEUTRAL"
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
    "broker_symbol": "EURJPY",
    "tick_time_utc": "2026-11-24T22:46:06Z",
    "bid": 174.59,
    "ask": 174.747,
    "digits": 3,
    "point": 0.001,
    "spread_points": 157.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -1.1e-11
  },
  "rtv": {
    "value": 0.36746302616609783,
    "baseline_median": 879.0,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-24T22:45:00Z"
  }
}
```
