# GBPAUD candidate evidence

JSON SHA-256: f32fce9c6b78ebf2835f20c11a3f51afab9cc4f80404931444f5973b942b7b24

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "GBPAUD",
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
      "path": "ohlc/pairs/GBPAUD/D1.json",
      "sha256": "aa11febf9455c6573b268552d56f87acb6d3f2ba7b1b5dc25ee187d10a932a90",
      "status": "STALE",
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
      "sha256": "a976ee59590a6dc4e4f22795d9e276aee9c4b76114b12d96f4df8cae64ff71bf",
      "status": "STALE",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPAUD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-25T02:01:09Z",
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
      "sha256": "d1da43991c8a358a81bb7be17c4fef6e92b5df899de0d84d34b8060286f67252",
      "status": "STALE",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPAUD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-25T04:01:11Z",
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
      "sha256": "1af25b6503535a8275c104ed29f6c7aa67ff9a327e948b5cb86d142c575f45e6",
      "status": "STALE",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "GBPAUD",
      "digits": 5,
      "retrieved_at_utc": "2026-11-25T04:31:10Z",
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
      "status": "STALE",
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
