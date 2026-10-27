# Trade Log — Robinhood Agentic Account

## 2026-10-27T16:23:37Z
- Action   : BUY BRO
- Price    : $67.48
- Amount   : $90.96 | Shares: 1.347956
- RSI      : 27.6 | EMA: BEARISH | BB: BELOW_BAND
- RL       : BUY conf=0.928 | BOOST (conf 2→3)
- Stop     : $66.35 (ATR) | Target: $74.23
- Strategy : normal | Sell date: ATR/signal
- Regime   : normal (regime shifted from bearish_ema this cycle)
- Reason   : RSI oversold+stabilizing (27.6↑) | BB reversal returning from band | RL BOOST

## 2026-10-27T16:23:41Z
- Action   : BUY HIG
- Price    : $132.87
- Amount   : $45.48 | Shares: 0.342289
- RSI      : 28.0 | EMA: BEARISH | BB: BELOW_BAND
- RL       : BUY conf=0.928 | BOOST (conf 2→3)
- Stop     : $131.65 (ATR) | Target: $146.16
- Strategy : normal | Sell date: ATR/signal
- Regime   : normal
- Reason   : RSI oversold+stabilizing (28.0↑) | BB reversal returning from band | RL BOOST

## 2026-10-27T16:23:44Z
- Action   : BUY AIG
- Price    : $79.41
- Amount   : $22.74 | Shares: 0.286362
- RSI      : 28.5 | EMA: BEARISH | BB: BELOW_BAND
- RL       : BUY conf=0.928 | BOOST (conf 2→3)
- Stop     : $78.81 (ATR) | Target: $87.35
- Strategy : normal | Sell date: ATR/signal
- Regime   : normal
- Reason   : RSI oversold+stabilizing (28.5↑) | BB reversal returning from band | RL BOOST

## 2026-10-27T15:26Z
- SUMMARY: Market open, in_window=true. 0 positions held. 0 SELLs. 0 BUYs: bearish_ema regime — 0 RSI BUYs (conf≥3 required), 0 net-buy BUYs, 0 surge. CB: daily 0.0%/weekly -0.2% (OK). BP=$231.91. Acct=$231.91. Universe=503.

## 2026-10-27T14:33Z
- SUMMARY: Market open, in_window=true. 0 positions held. 0 SELLs. 0 BUYs: bearish_ema regime — 0 RSI BUYs (conf≥3 required), 0 net-buy BUYs, 0 surge. CB: daily 0.0%/weekly -0.2% (OK). BP=$231.91. Acct=$231.91. Universe=503.

## 2026-10-26T20:19:31Z
- SUMMARY: Market closed. Buying power: $187.44. Equity positions: 0. Regime: bearish_ema. Account: $231.91. Universe fetched: 503. CB: daily -0.20%/weekly -0.20% (OK). No positions to sell. No BUYs (market closed).

## 2026-10-26T19:23:19Z
- SUMMARY: Market open, in_window=true. 0 positions held. 0 SELLs. 0 BUYs: bearish_ema regime — 0 RSI BUYs (conf≥3 required), 2 net-buy (AKAM $98.31 + NOC $564.48 — both conf<3, blocked by bearish_ema gate), 0 surge. CB: daily -0.20%/weekly -0.20% (OK). BP=$187.44. Acct=$231.91. Universe=503.

## 2026-10-26T18:22:22Z
- SUMMARY: Market open, in_window=true. 0 positions held. 0 SELLs. 0 BUYs: bearish_ema regime — 0 RSI BUYs (conf≥3 required in bearish_ema), 1 net-buy (AKAM $98.60 — conf<3 blocked by bearish_ema gate), 0 surge. CB: daily -0.20%/weekly -0.20% (OK). BP=$187.44. Acct=$231.91. Universe=503.

## 2026-10-26T17:18:27Z
- SUMMARY: Market open, in_window=true. 0 positions held. 0 SELLs. 0 BUYs: bearish_ema regime — 0 RSI BUYs (conf≥3 required in bearish_ema), 0 net-buy, 0 surge. CB: daily -0.2%/weekly -0.2% (OK). BP=$187.44 (acct_value=$231.91). Universe=503.

## 2026-10-26T15:24:04Z
- SUMMARY: Market open, in_window=true. 0 SELLs (VZ $43.79 > trail_stop $43.55, RSI=39.1 HOLD, pnl=-1.6%). 0 BUYs: bearish_ema regime — 0 RSI BUYs (conf>=3 required), 0 net-buy BUYs, 0 surge. CB: daily +0.1%/weekly +0.1% (OK). BP=$187.44. Acct=$232.55. Universe=503.

## 2026-10-20T16:18Z SUMMARY
- SUMMARY: Market open, in_window=true. 0 SELLs: CEG held <2h (entry 14:25Z, price $260.87 vs stop $254.32/target $286.86, no trigger). 1 BUY: CPRT $45.50 @ $27.37 (RSI BUY conf=2 + RL BOOST conf=0.974). CEG HOLD (low vol, RSI=27.3 oversold but signal skipped). Kill switch: trading_enabled=true. CB: daily -0.01%/weekly +0.22% (OK). BP=$95.49 post-order. Acct=$232.02. Universe=503.

## 2026-10-07T19:15:46Z [BACKFILL — prior cycle, not previously logged]
- Action   : SELL VTR
- Price    : $80.44
- Amount   : $18.88 | Shares: 0.234720
- RSI      : ~21.1 (oversold, HOLD) | EMA: BEARISH | BB: N/A
- RL       : null conf=null | null
- Stop     : $80.66 (ATR trail) triggered — price $80.44 ≤ $80.66
- Target   : $90.17 (+10%) — not reached
- Strategy : normal | Sell trigger: ATR trailing stop
- Regime   : normal
- Reason   : ATR trail stop hit: $80.44 ≤ $80.66; hours_held ~24h; PnL -1.87% from avg_cost $81.97. Exit per rule.

## 2026-10-07T19:08:28Z [BACKFILL — prior cycle, not previously logged]
- Action   : SELL GE
- Price    : $304.12
- Amount   : $38.02 | Shares: 0.125087
- RSI      : ~29.2 (near-oversold, HOLD) | EMA: BULLISH | BB: N/A
- RL       : null conf=null | null
- Stop     : $303.90 (ATR trail) triggered — price $304.12 ≥ $303.90 (price was near stop)
- Target   : $338.39 (+10%) — not reached
- Strategy : normal | Sell trigger: ATR trailing stop
- Regime   : normal
- Reason   : ATR trail stop triggered; hours_held ~29h; PnL -1.14% from avg_cost $307.63. Exit per rule.

## 2026-10-07T19:15:46Z [BACKFILL — prior cycle, not previously logged]
- Action   : SELL VTR
- Price    : $80.44
- Amount   : $18.88 | Shares: 0.234720
- RSI      : ~21.1 (oversold, HOLD) | EMA: BEARISH | BB: N/A
- RL       : null conf=null | null
- Stop     : $80.66 (ATR trail) triggered — price $80.44 ≤ $80.66
- Target   : $90.17 (+10%) — not reached
- Strategy : normal | Sell trigger: ATR trailing stop
- Regime   : normal
- Reason   : ATR trail stop hit: $80.44 ≤ $80.66; hours_held ~24h; PnL -1.87% from avg_cost $81.97. Exit per rule.

## 2026-10-07T19:08:28Z [BACKFILL — prior cycle, not previously logged]
- Action   : SELL GE
- Price    : $304.12
- Amount   : $38.02 | Shares: 0.125087
- RSI      : ~29.2 (near-oversold, HOLD) | EMA: BULLISH | BB: N/A
- RL       : null conf=null | null
- Stop     : $303.90 (ATR trail) triggered — price $304.12 ≥ $303.90 (price was near stop)
- Target   : $338.39 (+10%) — not reached
- Strategy : normal | Sell trigger: ATR trailing stop
- Regime   : normal
- Reason   : ATR trail stop triggered; hours_held ~29h; PnL -1.14% from avg_cost $307.63. Exit per rule.


## 2026-10-27T17:22:00Z
- Action  : HOLD (no trades)
- Regime  : normal (SPY above 200-EMA)
- Signals : 3 RSI BUY conf=2 (JKHY $158.80, MSCI $605.00, WM $234.66) — all blocked: investable $22.73×50%=$11.37 < $15 min order
- Holdings: BRO +0.01% ($90.97), HIG +0.65% ($45.77), AIG +0.55% ($22.86) — ~1h held, no exit triggers
- TrailUp : BRO 66.35→66.64 | HIG 131.65→132.81 | AIG 78.81→79.39
- CB      : daily +0.18% / weekly -0.01% (OK, floor=$200.00)
- BP      : $72.73 | Acct=$232.34 | Universe=503
