# GBPUSD candidate evidence

JSON SHA-256: 382615646a84d6e52e0fc756d72b3182857abc1d69819db9457e719e8781e138

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "GBPUSD",
  "as_of_utc": "2026-11-24T08:45:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/GBPUSD/D1.json",
      "sha256": "bb22c6d501d0828db858da0e826379ca2f5fd564574f80f8f293b0e31e4cdfb1",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPUSD",
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
    },
    "H4": {
      "path": "ohlc/pairs/GBPUSD/H4.json",
      "sha256": "bef3e197d7904c0a8143cfb77f1ea5cc36cf786c2a69704c27d1ad606f1de9fd",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T06:01:10Z",
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
      "path": "ohlc/pairs/GBPUSD/H1.json",
      "sha256": "f6323b333581099b5430c5898b4333b1f88df87ff260ee2caa0181bbec57682e",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T08:01:11Z",
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
      "path": "ohlc/pairs/GBPUSD/M15.json",
      "sha256": "c4538096994864424c713d2b8eb640c7c7b3d004a74550962656dc96fa96e25a",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T08:46:08Z",
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
      "path": "ohlc/pairs/GBPUSD/W1.json",
      "sha256": "798f5481b0b05e4fbc0b0a97f906282eaa21bb948bf0416fa82f50a013658390",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPUSD",
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
      "last_closed_bar_utc": "2026-11-23T22:00:00Z",
      "close": 1.3030300000000001,
      "ema": {
        "20": 1.3234928186708628,
        "50": 1.3303235431200122,
        "200": 1.3364769345742238
      },
      "ema20_change_5bars": -0.008588280690063232,
      "atr14": 0.007702609502040868,
      "trend": "SELL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-24T06:00:00Z",
      "close": 1.30411,
      "ema": {
        "20": 1.3094352343721427,
        "50": 1.3163527947792164,
        "200": 1.3281917412343112
      },
      "ema20_change_5bars": -0.003554277466641498,
      "atr14": 0.003027989474463221,
      "trend": "SELL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-24T08:00:00Z",
      "close": 1.30383,
      "ema": {
        "20": 1.304686667604413,
        "50": 1.307239130976345,
        "200": 1.3162439042069696
      },
      "ema20_change_5bars": -0.0005577569399413118,
      "atr14": 0.0012830230828966966,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-24T08:45:00Z",
      "close": 1.3048199999999999,
      "ema": {
        "20": 1.3039794937718574,
        "50": 1.3041399923612855,
        "200": 1.3072609800575667
      },
      "ema20_change_5bars": 7.869627129730716e-06,
      "atr14": 0.0007074321162736686,
      "trend": "NEUTRAL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-21T22:00:00Z",
      "close": 1.30804,
      "ema": {
        "20": 1.3340904464101146,
        "50": 1.3359641189399871,
        "200": 1.313212187018977
      },
      "ema20_change_5bars": -0.004948912869944921,
      "atr14": 0.016688213870419927,
      "trend": "SELL"
    }
  },
  "candidates": [
    {
      "symbol": "GBPUSD",
      "enabled": 0,
      "direction": "SELL",
      "mode": "PULLBACK",
      "zone_low": 1.30458,
      "zone_high": 1.30496,
      "invalidation": 1.30528,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.75,
      "factor_group": "USD_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 0.0,
      "pivot": {
        "side": "HIGH",
        "level": 1.30477,
        "index": 997,
        "confirmed_index": 999,
        "pivot_utc": "2026-11-24T06:00:00Z",
        "confirmed_utc": "2026-11-24T08:00:00Z"
      },
      "breakout_close_utc": null,
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": false,
      "valid_until_utc": "2026-11-25T08:45:00Z"
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
    "broker_symbol": "GBPUSD",
    "tick_time_utc": "2026-11-24T08:46:07Z",
    "bid": 1.30474,
    "ask": 1.30483,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 9.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": 8e-12
  },
  "rtv": {
    "value": 2.07475317348378,
    "baseline_median": 709.0,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-24T08:45:00Z"
  }
}
```
