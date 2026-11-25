# CHFJPY candidate evidence

JSON SHA-256: 2ed85a284db01e6f97dae8481e4c68bdd7faf56903dd0054933c221c69f02b62

Publisher-calculated, not independently recomputed by reader.

```json
{
  "schema": "g7_candidate.v1",
  "algorithm_version": "zones-1.0",
  "symbol": "CHFJPY",
  "as_of_utc": "2026-11-25T01:30:00Z",
  "price_basis": "BID",
  "status": "REJECT",
  "reasons": [
    "D1_H4_TREND_CONFLICT"
  ],
  "sources": {
    "D1": {
      "path": "ohlc/pairs/CHFJPY/D1.json",
      "sha256": "14e8359478e6829392538dae083164d55c408a0afa2bd4b71f3eea6c66aef545",
      "status": "OK",
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
      "sha256": "238a35b200be79d60eb9eaf1b708bd18687533bcf793b7caef8afd1900bb06e3",
      "status": "OK",
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
    "H1": {
      "path": "ohlc/pairs/CHFJPY/H1.json",
      "sha256": "9c0c9d25bbc5572d526f48681b15169f2f76164a8b71bb26d42e228aeb59ef82",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CHFJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-25T01:01:12Z",
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
      "sha256": "334e4e657307591884beb2e57102a57f411b3b6697b11ff3862b01363a747946",
      "status": "OK",
      "broker_server": "ICMarketsSC-MT5-6",
      "broker_symbol": "CHFJPY",
      "digits": 3,
      "retrieved_at_utc": "2026-11-25T01:31:12Z",
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
      "status": "OK",
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
  "metrics": {
    "D1": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-24T22:00:00Z",
      "close": 190.561,
      "ema": {
        "20": 190.5281113723003,
        "50": 191.4458284183102,
        "200": 194.29417081247647
      },
      "ema20_change_5bars": -0.7918849459902617,
      "atr14": 1.2061720472513644,
      "trend": "SELL"
    },
    "H4": {
      "bars_used": 500,
      "last_closed_bar_utc": "2026-11-24T22:00:00Z",
      "close": 190.561,
      "ema": {
        "20": 189.5519178004079,
        "50": 189.91997978259133,
        "200": 190.99778005483563
      },
      "ema20_change_5bars": 0.3453344592072085,
      "atr14": 0.5080180046741575,
      "trend": "NEUTRAL"
    },
    "H1": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-25T01:00:00Z",
      "close": 190.519,
      "ema": {
        "20": 190.15403383953782,
        "50": 189.7092605689909,
        "200": 189.92829287551638
      },
      "ema20_change_5bars": 0.24675109030599174,
      "atr14": 0.24220835064243837,
      "trend": "BUY"
    },
    "M15": {
      "bars_used": 1000,
      "last_closed_bar_utc": "2026-11-25T01:30:00Z",
      "close": 190.468,
      "ema": {
        "20": 190.510427444583,
        "50": 190.35706556511175,
        "200": 189.71089340157187
      },
      "ema20_change_5bars": 0.0015862056629032395,
      "atr14": 0.11530642988567039,
      "trend": "BUY"
    },
    "W1": {
      "bars_used": 300,
      "last_closed_bar_utc": "2026-11-21T22:00:00Z",
      "close": 188.664,
      "ema": {
        "20": 193.09590454106697,
        "50": 193.88062865360095,
        "200": 174.95206456286553
      },
      "ema20_change_5bars": -1.6577180467520805,
      "atr14": 2.8955846156205403,
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
    "broker_symbol": "CHFJPY",
    "tick_time_utc": "2026-11-25T01:31:06Z",
    "bid": 190.484,
    "ask": 190.496,
    "digits": 3,
    "point": 0.001,
    "spread_points": 12.0,
    "server_time_utc_offset_minutes_at_collection": 120,
    "status": "OK",
    "spread_rounding_deviation_points": -0.0
  },
  "rtv": {
    "value": 2.560377358490566,
    "baseline_median": 530.0,
    "semantics": "MT5_TICK_VOLUME",
    "session_adjusted": false,
    "last_closed_bar_utc": "2026-11-25T01:30:00Z"
  }
}
```
