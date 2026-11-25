# CHFJPY candidate evidence

JSON SHA-256: 97ed6f57433d1df4b1be8014e977a1411ccbe139831809f3324d8e8a1c3e70b2

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "CHFJPY",
  "as_of_utc": "2026-11-25T04:45:00Z",
  "price_basis": "BID",
  "status": "REJECT",
  "reasons": [
    "D1:SOURCE_NOT_VALID",
    "H4:SOURCE_NOT_VALID",
    "H1:SOURCE_NOT_VALID",
    "M15:SOURCE_NOT_VALID"
  ],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/CHFJPY/D1.json",
      "sha256": "14e8359478e6829392538dae083164d55c408a0afa2bd4b71f3eea6c66aef545",
      "status": "STALE",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CHFJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-24T22:01:34Z",
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
      "path": "ohlc/pairs/CHFJPY/H4.json",
      "sha256": "31594d69e309ec8dc2221d5409a0d27582f60cb7444e5492df182c204e779357",
      "status": "STALE",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CHFJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-25T02:01:11Z",
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
      "path": "ohlc/pairs/CHFJPY/H1.json",
      "sha256": "9465b7ba67e5029b1244a2fbdf64eadbeee43dbb3fe2bf3aa1e11b628ffa1b8d",
      "status": "STALE",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CHFJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-25T04:01:13Z",
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
      "path": "ohlc/pairs/CHFJPY/M15.json",
      "sha256": "3978277a8b07e9ac1c6136d936f0dc40d989e49aa170557633b7bae4f3010fd3",
      "status": "STALE",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CHFJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-25T04:31:11Z",
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
      "path": "ohlc/pairs/CHFJPY/W1.json",
      "sha256": "3219665e078c0b7c18a3526e834a971485ea5bd1b42228f652f3313afef1d1ae",
      "status": "STALE",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CHFJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-24T03:31:11Z",
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
  "metrics": {},
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
    "broker_symbol": null,
    "tick_time_utc": null,
    "bid": null,
    "ask": null,
    "digits": null,
    "point": null,
    "spread_points": null,
    "server_time_utc_offset_minutes_at_collection": null,
    "status": "ERROR"
  }
}
```
