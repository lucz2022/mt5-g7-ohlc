# AUDCHF candidate evidence

JSON SHA-256: 007f2365a096856adc43d3d2dfd2e2ffb024a967c92aa573b800a5e7f247bd46

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "AUDCHF",
  "as_of_utc": "2026-11-25T11:15:00Z",
  "price_basis": "BID",
  "status": "WATCH",
  "reasons": [
    "NO_VALID_NEARBY_ZONE"
  ],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/AUDCHF/D1.json",
      "sha256": "333408684f7525641d9dc632f97ac456e53cb48ebc2857179d4be5d72958881b",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDCHF",
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
      "path": "ohlc/pairs/AUDCHF/H4.json",
      "sha256": "7db0f0a5fd9231a1e0ea9de3629a8c482b362b74c410100bba61056bcfec1255",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDCHF",
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
      "path": "ohlc/pairs/AUDCHF/H1.json",
      "sha256": "e14f430baf98310b386d4269483e6172a736820b4ea3879a7c5edb393ec7d358",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-25T11:16:15Z",
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
      "sha256": "429cfcec97b769f715b440a8c6052bab3a89e31757f8cab31a6aa3f7db6d39d9",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDCHF",
      "digits": 5,
      "retrieved_at_utc": "2026-11-25T11:16:15Z",
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
      "sha256": "108a2191b6e9a84a59742c954a28f2fe2bdf7d85538ce48d63275de52c664f44",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "AUDCHF",
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
  "metrics": {
    "D1": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-24T22:00:00Z",
      "close": 0.55481,
      "ema": {
        "20": 0.5664010940820242,
        "50": 0.5716745012510311,
        "200": 0.5652269138148386
      },
      "ema20_change_5bars": -0.0049824256566812775,
      "atr14": 0.005214112451858275,
      "trend": "SELL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-25T10:00:00Z",
      "close": 0.54792,
      "ema": {
        "20": 0.5565360352066834,
        "50": 0.5608418722340669,
        "200": 0.569647268126807
      },
      "ema20_change_5bars": -0.0027129455019436755,
      "atr14": 0.002647808565726371,
      "trend": "SELL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-25T11:00:00Z",
      "close": 0.54698,
      "ema": {
        "20": 0.5519685832337414,
        "50": 0.5547979347204509,
        "200": 0.5608793723004463
      },
      "ema20_change_5bars": -0.002449195301570173,
      "atr14": 0.001473290542723135,
      "trend": "SELL"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-25T10:45:00Z",
      "close": 0.54698,
      "ema": {
        "20": 0.5487791639754274,
        "50": 0.5509446535360671,
        "200": 0.5549708155248124
      },
      "ema20_change_5bars": -0.0009811535931378845,
      "atr14": 0.0008401659641562294,
      "trend": "SELL"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-21T22:00:00Z",
      "close": 0.55591,
      "ema": {
        "20": 0.5706053552543319,
        "50": 0.5620488215813056,
        "200": 0.5796629162759163
      },
      "ema20_change_5bars": -0.0015468899505538536,
      "atr14": 0.009907778232017057,
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
    "broker_symbol": "AUDCHF",
    "tick_time_utc": "2026-11-25T11:16:07Z",
    "bid": 0.54703,
    "ask": 0.54715,
    "digits": 5,
    "point": 1e-05,
    "spread_points": 12.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -1e-12
  },
  "rtv": {
    "value": 0.09419496166484119,
    "baseline_median": 1369.5,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-25T10:45:00Z"
  }
}
```
