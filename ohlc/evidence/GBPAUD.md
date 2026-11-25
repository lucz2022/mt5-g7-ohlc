# GBPAUD candidate evidence

JSON SHA-256: 9512f99ed768df2c571081959b8cdb5e078ef3b15e21f8d2e8ae8115d0e19cf4

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "GBPAUD",
  "as_of_utc": "2026-11-25T09:45:00Z",
  "price_basis": "BID",
  "status": "WATCH",
  "reasons": [
    "NO_VALID_NEARBY_ZONE"
  ],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/GBPAUD/D1.json",
      "sha256": "aa11febf9455c6573b268552d56f87acb6d3f2ba7b1b5dc25ee187d10a932a90",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPAUD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T22:01:31Z",
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
      "path": "ohlc/pairs/GBPAUD/H4.json",
      "sha256": "f1a500c03a5cd8ec3dadbed8b46d21381847656a8019e920e5b50198f4e9428d",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPAUD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-25T06:01:13Z",
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
      "path": "ohlc/pairs/GBPAUD/H1.json",
      "sha256": "9b0cea100af44bfc7145a0d98f8e534b717ce92cafab90e530a811e28ab51755",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPAUD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-25T09:01:11Z",
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
      "path": "ohlc/pairs/GBPAUD/M15.json",
      "sha256": "35ac9573423a77a27b3346bca14051e4daac42ce4d848edb2210a858ec7dbd4b",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPAUD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-25T09:46:13Z",
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
      "path": "ohlc/pairs/GBPAUD/W1.json",
      "sha256": "8e4bdefff8fc4aa15391a1bf04a7c7a6477b4e569e595d41112f226cb2f9168f",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPAUD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T03:31:10Z",
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
      "close": 1.97475,
      "ema": {
        "20": 1.9458702761900233,
        "50": 1.9248167929015738,
        "200": 1.9229070519260492
      },
      "ema20_change_5bars": 0.01489521953923889,
      "atr14": 0.01286843201733804,
      "trend": "BUY"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-25T06:00:00Z",
      "close": 1.98562,
      "ema": {
        "20": 1.9713400016363103,
        "50": 1.962765643469971,
        "200": 1.9338468190593603
      },
      "ema20_change_5bars": 0.0038189756987947465,
      "atr14": 0.006431623719872946,
      "trend": "BUY"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-25T09:00:00Z",
      "close": 1.98975,
      "ema": {
        "20": 1.9799725330154554,
        "50": 1.974869077012516,
        "200": 1.9631699481838867
      },
      "ema20_change_5bars": 0.005435030104241401,
      "atr14": 0.003975363348721009,
      "trend": "BUY"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-25T09:45:00Z",
      "close": 1.98868,
      "ema": {
        "20": 1.9878077477892269,
        "50": 1.9831834336199734,
        "200": 1.9750659997306201
      },
      "ema20_change_5bars": 0.0011267621768868974,
      "atr14": 0.0019096459669728076,
      "trend": "BUY"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-21T22:00:00Z",
      "close": 1.97606,
      "ema": {
        "20": 1.9161852178864056,
        "50": 1.929110636085068,
        "200": 1.9263219750354215
      },
      "ema20_change_5bars": 0.01466242579485888,
      "atr14": 0.0251286831077751,
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
    "broker_symbol": "GBPAUD",
    "tick_time_utc": "2026-11-25T09:46:09Z",
    "bid": 1.98895,
    "ask": 1.9891100000000002,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 16.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -1.6e-11
  },
  "rtv": {
    "value": 1.0278800631246712,
    "baseline_median": 1901.0,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-25T09:45:00Z"
  }
}
```
