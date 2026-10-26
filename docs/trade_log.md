# Trade Log — Robinhood Agentic Account

## 2026-10-26T16:20:06Z
- Action   : SELL VZ
- Price    : $43.18
- Amount   : $44.48 | Shares: 1.030160
- RSI      : 40.37 | EMA: BEARISH | BB: IN_BAND
- RL       : null conf=null | null
- Stop     : $43.55 (trail, triggered) | Target: $48.93
- Strategy : intraday_surge | Sell date: ATR/signal
- Regime   : bearish_ema
- Reason   : ATR trailing stop hit — price $43.18 ≤ trail_stop $43.55 (−2.9% from avg_cost $44.48). EMA=BEARISH. Market sell order placed (ID: 6adf7db6).

## 2026-10-26T16:20:30Z
- SUMMARY: Market open, in_window=true. 1 SELL: VZ $43.18 (ATR trail stop $43.55 triggered, pnl≈-2.9%). 0 BUYs: bearish_ema regime — 0 RSI BUYs (conf>=3 required), 0 net-buy, 0 surge. CB: daily 0.19%/weekly 0.19% (OK). Kill switch: trading_enabled=true. BP≈$231.92 (post-sell). Acct≈$231.92. Universe=503.

## 2026-10-26T14:34:39Z
- SUMMARY: Market open, in_window=true. 0 SELLs: VZ at $43.61 (trail_stop $43.55 not hit, pnl=-2.0%, hours_held=67h, RSI=HOLD, no SELL signal). 0 BUYs: bearish_ema regime — 0 RSI BUYs (conf>=3 required), 2 net-buy BUYs blocked (AKAM, SNA — one strategy only, bearish_ema requires conf>=3). 18 RSI SELL signals on non-held tickers (XOM, CVX, SLB, HON, NOW, CRWD et al). CB: daily 0.0%/weekly 0.0% (OK, new week reset). Kill switch: trading_enabled=true. BP=$187.44. Acct=$232.37. Universe=503. VZ: RSI=53.5 EMA=BULLISH BB=IN_BAND HOLD. Trail_stop=$43.55 (0.1% above stop — watch closely next cycle).

## 2026-10-23T20:20:00Z
- SUMMARY: Market closed (closed at 20:00 UTC / 16:00 ET). 0 SELLs (VZ held: price $44.55 > trail_stop $43.55, pnl=+0.2%, hours_held<3). 0 BUYs: market closed. Regime=bearish_ema. Kill switch: trading_enabled=true. CB: daily +0.03%/weekly +0.34% (OK). BP=$187.44. Acct=$233.33. Universe=503. VZ: RSI=53.5 EMA=BULLISH HOLD.

## 2026-10-23T19:20:10Z
- Action   : BUY VZ
- Price    : $44.47
- Amount   : $45.82 | Shares: 1.0304
- RSI      : 51.28 | EMA: BULLISH | BB: IN_BAND
- RL       : HOLD conf=0.928 | null (not SELL veto, proceed normally)
- Stop     : $43.55 | Target: $48.92
- Strategy : intraday_surge | Sell date: ATR/signal
- Regime   : bearish_ema (position halved ×0.5×0.5=×0.25)
- Reason   : Intraday surge count=2 (buy vol +46.8% over 2 cycles) | buy vol 7.18M vs 4.89M prior day | Net buy reversed positive 1.94M | SPY RSI=34.84 EMA=BEARISH

## 2026-10-23T18:20:30Z
- SUMMARY: Market open, in_window=true. 0 SELLs (no positions). 0 BUYs: bearish_ema regime — 0 RSI BUYs (conf>=3 required), 0 net-buy BUYs, 0 surge (VZ count=1 need>=2, CNC 6.9%<10%). SPY EMA=BEARISH. CB: daily 0.0%/weekly -0.31% (OK). Kill switch: trading_enabled=true. BP=$233.26. Acct=$233.26. Universe=503.

## 2026-10-23T17:21:07Z
- SUMMARY: Market open, in_window=true. 0 SELLs (no positions). 0 BUYs: bearish_ema regime — 0 RSI BUYs (conf>=3 required), 1 net-buy (HONA blocked: bearish_ema requires conf>=3, net-buy only). SPY RSI=36.20 EMA=BEARISH. CB: daily 0.0%/weekly -0.31% (OK). BP=$233.26. Acct=$233.26. Universe=503.

## 2026-10-23T14:21:00Z
- SUMMARY: Market open, in_window=true. 0 SELLs (no positions). 0 BUYs: bearish_ema regime (SPY RSI=40.19, below 200-EMA): 0 RSI BUYs, 5 net-buy-only signals (BAC/IBM/SWKS/SW/HSIC conf=2, blocked by bearish_ema 3/3 requirement). Surge: IBM/HSIC/SHW/LDOS/AVY/URI/MAA/ULTA/PRU/AAPL/HSY/LYV/CSX count=1 (need≥2). CB: daily 0.0%/weekly -0.31% (OK, acct up from week start). Kill switch: trading_enabled=true. BP=$233.26. Acct=$233.26. Universe=503.

## 2026-10-22T19:19:43Z
- SUMMARY: Market open, in_window=true. 0 SELLs (no positions). 0 BUYs: investable=$0 (BP=$50.00=cash buffer, T+2 unsettled). bearish_ema regime: 0 RSI BUYs. 8 net-buy signals (BAC/SW/LDOS/URI/AVY/MAA/ULTA/PRU). Surge: LDOS/URI/AVY/ULTA/PRU/GDDY count=1 (need>=2). CB: daily +0.28%/weekly +0.31% (OK). Kill switch: trading_enabled=true. BP=$50.00. Acct=$233.26. Universe=503.

## 2026-10-22T17:21:00Z
- SUMMARY: Market open, in_window=true. 0 SELLs (no positions). 0 BUYs: investable=$0 (BP=$50.00=cash buffer, T+2 unsettled from CPRT sell). bearish_ema regime: 0 RSI BUYs. 5 net-buy signals (BAC/SW/DECK/URI/ULTA, conf unknown, investable=$0 anyway). Surge: AEP/DUK/CNP/DG count=1 (need>=2, replaced GRMN/VST/GWW). CB: daily -0.28%/weekly -0.31% (OK, acct slightly up). Kill switch: trading_enabled=true. BP=$50.00. Acct=$233.26. Universe=503.

## 2026-10-22T16:21:35Z
- SUMMARY: Market open, in_window=true. 1 SELL: CPRT RSI overbought $28.885 (+5.54%, +$2.52). 0 BUYs: investable=$0 (BP=$50.00=cash buffer, T+2 unsettled). bearish_ema regime: 0 RSI BUYs. Surge: GRMN/VST/GWW count=1 (no change). CB: daily +0.28%/weekly +0.31% (OK). Kill switch: trading_enabled=true. BP=$50.00. Acct=$233.26. Universe=503.
- Action : SELL CPRT
- Price  : $28.885
- Amount : $48.00 (1.66241 shares)
- RSI    : 70.6 | EMA: BULLISH | BB: ABOVE_BAND
- Entry  : $27.37 | Held: ~48h (since 2026-10-20T16:18Z)
- PnL    : +$2.52 (+5.54%)
- Stop   : $28.054 | Target: $30.107
- Reason : RSI overbought (70.6) | price above BB upper band

## 2026-10-22T15:22:26Z
- SUMMARY: Market open, in_window=true. 0 SELLs: CPRT $28.755 > stop $28.05 < target $30.11 (HOLD, RSI=66.9, RL=null). ATR ratchet: CPRT trail_stop $27.51→$28.05 (profit +5.06% ≥ 5% threshold, new_stop=avg_cost×1.025=$28.05). 0 BUYs: bearish_ema regime requires conf 3/3 — 0 RSI BUYs, 3 net-buy-only BUYs (BAC/SW/DDOG conf=2, blocked). Surge: GRMN/VST/GWW count=1 (need≥2, no new surges this cycle). Regime: BEARISH_EMA (SPY below 200-EMA). CB: daily -0.19%/weekly -0.22% (OK). Kill switch: trading_enabled=true. BP=$50.00. Acct=$233.05. Universe=503.

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

