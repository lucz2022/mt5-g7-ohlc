# CADCHF candidate evidence

JSON SHA-256: f1742013c307c79b2f84762a29c9c80eb1dfc8a1660c6983d4cc9826c281229e

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "CADCHF",
  "as_of_utc": "2026-11-25T10:15:00Z",
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
      "path": "ohlc/pairs/CADCHF/D1.json",
      "sha256": "d21e1fd50cf81eba0816e5d1eaae84a8fd8215a3bc8cbb64d40d63e4ce8d6f4d",
      "status": "STALE",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CADCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-24T22:01:33Z",
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
      "path": "ohlc/pairs/CADCHF/H4.json",
      "sha256": "995dbb7a0787c71e938d2d0feb1318923ace5d17dabcadd0aa1a0089337622ea",
      "status": "STALE",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CADCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-25T10:01:14Z",
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
      "path": "ohlc/pairs/CADCHF/H1.json",
      "sha256": "d3ea1d814727a33c9279d6815e0dfdb70962cb1f080ab0f1991780367cbe0c64",
      "status": "STALE",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CADCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-25T10:01:14Z",
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
      "path": "ohlc/pairs/CADCHF/M15.json",
      "sha256": "ccd2b1ebd5a074dab2e3f077c859814308954fccfc36c16e2520ecc77faac97f",
      "status": "STALE",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CADCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-25T10:01:14Z",
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
      "path": "ohlc/pairs/CADCHF/W1.json",
      "sha256": "e596cdd2887d72f322752a944029e4270e21df5e9ad6530da6fe9c890e1ff7a7",
      "status": "STALE",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CADCHF",
      "digits": 5,
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
