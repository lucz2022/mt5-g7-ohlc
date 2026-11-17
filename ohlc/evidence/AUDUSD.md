# AUDUSD candidate evidence

JSON SHA-256: ec08b51ac88b0e1829793329d0e438e5b2a8b39fc3f68c8c65f0602d34a75498

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "AUDUSD",
  "as_of_utc": "2026-11-17T03:00:00Z",
  "price_basis": "BID",
  "status": "TECHNICAL_CANDIDATE",
  "reasons": [],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/AUDUSD/D1.json",
      "sha256": "07906ed2f75436c4139c722f7dd6b42c1e3d6971984c399fbcddc1d2db17ff18",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T22:01:15Z",
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
      "sha256": "4108ff43c67409f59ef0799bfaf476979ff7fb6242e84aeb69a4d077ca346f1a",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-17T02:01:09Z",
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
      "sha256": "61b172bd1b417d3942736a47c8be8a8f5627cdef6a57d6aa6cfd8ee759ba167f",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-17T03:01:11Z",
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
      "sha256": "7d75fc64c61e11386d83d962d6d42864f4e7e796322a705ae4c20ad0f81e1240",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-17T03:01:11Z",
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
      "sha256": "25c2a0c8870e04b454e6ce7a4a1c8690f066cf44b1f36ee497683c1b2e99101f",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDUSD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-16T02:33:12Z",
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
      "close": 0.67377,
      "ema": {
        "20": 0.6909584772695866,
        "50": 0.6975735353922017,
        "200": 0.6970384543805297
      },
      "ema20_change_5bars": -0.007161004905882229,
      "atr14": 0.005390982454549201,
      "trend": "SELL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-17T02:00:00Z",
      "close": 0.67368,
      "ema": {
        "20": 0.6786588333376622,
        "50": 0.6848785306063457,
        "200": 0.6952132506317438
      },
      "ema20_change_5bars": -0.002767965798066707,
      "atr14": 0.0018235681966293873,
      "trend": "SELL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-17T03:00:00Z",
      "close": 0.67412,
      "ema": {
        "20": 0.6745845174526067,
        "50": 0.676711453224485,
        "200": 0.684932167837213
      },
      "ema20_change_5bars": -0.0005728721722461083,
      "atr14": 0.0008726767431374726,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-17T03:00:00Z",
      "close": 0.67412,
      "ema": {
        "20": 0.6737340405533664,
        "50": 0.6740814080690397,
        "200": 0.6767418186710557
      },
      "ema20_change_5bars": 0.00010791628368089778,
      "atr14": 0.0004632732679790574,
      "trend": "NEUTRAL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-14T22:00:00Z",
      "close": 0.67708,
      "ema": {
        "20": 0.6998130798434226,
        "50": 0.6940327483605638,
        "200": 0.6827272344123759
      },
      "ema20_change_5bars": -0.005248907040624307,
      "atr14": 0.011269457735274473,
      "trend": "NEUTRAL"
    }
  },
  "candidates": [
    {
      "symbol": "AUDUSD",
      "enabled": 0,
      "direction": "SELL",
      "mode": "BREAKOUT",
      "zone_low": 0.67405,
      "zone_high": 0.67431,
      "invalidation": 0.67453,
      "tp1": 0,
      "tp2": 0,
      "rr1": 1.2,
      "rr2": 2.5,
      "risk_pct": 0.75,
      "factor_group": "USD_LONG",
      "status": "WAIT_CONFIRM",
      "distance_atr": 0.0,
      "pivot": {
        "side": "LOW",
        "level": 0.67418,
        "index": 988,
        "confirmed_index": 990,
        "pivot_utc": "2026-11-16T16:00:00Z",
        "confirmed_utc": "2026-11-16T18:00:00Z"
      },
      "breakout_close_utc": "2026-11-16T19:00:00Z",
      "zone_rule": "pivot +/- 0.15 H1 ATR14; stop beyond zone by 0.25 ATR14",
      "pending": [
        "MACRO_REVIEW",
        "EVENT_REVIEW",
        "EA_LIVE_CHECKS"
      ],
      "m15_direction_confirmed": false,
      "valid_until_utc": "2026-11-18T03:00:00Z"
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
    "broker_symbol": "AUDUSD",
    "tick_time_utc": "2026-11-17T03:01:09Z",
    "bid": 0.67412,
    "ask": 0.67421,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 9.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": 8e-12
  },
  "rtv": {
    "value": 1.7801494130202775,
    "baseline_median": 468.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-17T03:00:00Z"
  }
}
```
