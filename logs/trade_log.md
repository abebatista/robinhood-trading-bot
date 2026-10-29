# Trade Log — Robinhood Agentic Account

## 2026-10-29T17:24:27Z (SUMMARY)
- SUMMARY: Market OPEN, in_window=true. Regime: normal (SPY above 200-EMA). 0 SELLs: ABNB ($166.97, trail_stop $166.37, -0.44%, <3h hold), ELV ($420.27, trail_stop $414.29, +0.51%, <3h hold), TTWO ($192.70, trail_stop $192.26, -1.29%, <3h hold) — no exit triggers. 0 BUYs: investable=$0 (BP=$50−$50 buffer). RSI BUYs=4 (SNOW/CRWD/BSX conf=2; TTWO conf=2 already held). Surge: none. CB: daily 0.32%/weekly 1.13% (OK). BP=$50.00. Equity positions: 3. Account: $229.74. Universe=503 (297 tickers fetched from RH historicals this cycle).

## 2026-10-29T16:43:58Z (SUMMARY)
- SUMMARY: Market OPEN, in_window=true. Regime: normal (SPY above 200-EMA). 0 SELLs: ABNB+ELV <3h hold, no exit triggers. 1 BUY: TTWO (RSI 26.7 oversold+stabilizing, BB reversal, RL BOOST conf=0.928, $45.12, order 6ae377ce). CB: daily 0.01%/weekly 0.82% (OK). BP=$50.00 post-trade. Acct≈$230.51. Universe=503.

## 2026-10-29T16:43:58Z
- Action   : BUY TTWO
- Price    : $195.15
- Amount   : $45.12 | Shares: 0.2312
- RSI      : 26.74 | EMA: BEARISH | BB: BELOW_BAND
- RL       : BUY conf=0.928 | BOOST
- Stop     : $192.26 | Target: $214.67
- Strategy : normal | Sell date: ATR/signal
- Regime   : normal
- Reason   : RSI oversold+stabilizing (28.0→26.7) | BB reversal returning from band | RL BOOST (0.928)

## 2026-10-28T19:20:00Z (SUMMARY)
- SUMMARY: Market OPEN, in_window=true. Regime: normal. 1 SELL: AIG (ATR trail stop $79.645≤$79.66, +0.30%, order 6ae24ad1). 0 BUYs: investable=$0 (BP=$50−$50 buffer; sell proceeds unsettled). AMAT surge count=2 (buy candidate, but $0 investable). 0 positions. CB: daily 0.22%/weekly 0.81% (OK). BP=$50.00. Acct=$230.48. Universe=503.

## 2026-10-28T19:19:45Z
- Action   : SELL AIG
- Price    : $79.645
- Amount   : $22.82 | Shares: 0.286362
- RSI      : 35.7 | EMA: BEARISH | BB: IN_BAND
- RL       : null conf=null | null
- Stop     : $79.66 | Target: $87.35
- Strategy : normal | Sell date: ATR trail stop
- Regime   : normal
- Reason   : ATR trailing stop triggered ($79.645 ≤ $79.66). Entry 2026-10-27T16:23Z, held ~27h. PnL: +0.30% (+$0.07). Net-buy regime neutral (AIG=HOLD, low volume 0.28x avg). Order id: 6ae24ad1.

## 2026-10-28T18:27:00Z (SUMMARY)
- SUMMARY: Market OPEN, in_window=true. Regime: normal. 0 SELLs: AIG above trail stop ($79.97>$79.66, no signal). 0 BUYs: investable=$0 (BP=$50.00−$50 buffer). Trail stop ratcheted: AIG $79.39→$79.66 (ATR 0.38%). Surge: no candidates (AMAT/EME/BXP count=1, need 2). 1 position: AIG(+0.70%). CB: daily 0.20%/weekly 0.79% (OK). BP=$50.00. Acct=$230.53. Universe=503.

## 2026-10-28T17:27:00Z (SUMMARY)
- SUMMARY: Market OPEN, in_window=true. Regime: normal. 1 SELL: GDDY (net_buy_sell_signal — net buy reversed 0.04M→0.01M, OBV -0.2M/day, held ~21h, +0.57%). 0 BUYs: buying_power=$50.00 after SELL, investable=$0 ($50−$50 buffer; GDDY proceeds unsettled). 1 position: AIG(+0.89%, trail=$79.39). CB: daily 0.18%/weekly 0.77% (OK). Surge: GEV removed (no longer 10%+ surge). BP=$50.00. Acct=$230.57. Universe=503 (41 tickers in RH cache, Strategy 2 ran 503).

## 2026-10-28T17:26:00Z
- Action   : SELL GDDY
- Price    : $106.07
- Amount   : $22.86 | Shares: 0.215511
- RSI      : 37.5 | EMA: BEARISH | BB: IN_BAND
- RL       : null conf=null | null
- Stop     : $103.53 | Target: $116.02
- Strategy : normal | Sell: net_buy_sell_signal
- Regime   : normal
- Reason   : Net buy trend reversed (0.04M → 0.01M, OBV -0.2M/day). Held ~21h since 2026-10-27T19:21Z. PnL: ~+0.57% (+$0.13). Order id: 6ae23027.

## 2026-10-28T16:26:00Z (SUMMARY)
- SUMMARY: Market OPEN, in_window=true. Regime: normal. 0 SELLs: AIG(stop=$79.39<price=$80.12,no signal), GDDY(stop=$103.53<price=$106.24,no signal). 0 BUYs: investable=$0 (BP=$50.00 − $50 buffer; sell proceeds unsettled). Surge: GEV count=1 (needs 2). RSI BUY queue: META/BA/ICE/MPC/MNST/VLO/XYL (conf=2) — no investable capital. 2 positions: AIG(+0.89%)/GDDY(+0.73%). CB: daily 0.16%/weekly 0.75% (OK). Trail stops: AIG=$79.39, GDDY=$103.53. BP=$50.00. Acct=$230.62. Universe=503.

## 2026-10-28T15:22:45Z (SUMMARY)
- SUMMARY: Market OPEN, in_window=true. Regime: normal. 2 SELLs: BRO ATR-trail-stop ($66.51≤$66.64), HIG ATR-trail-stop ($131.98≤$132.81). 0 BUYs: investable=$0 (BP=$50 − $50 buffer; sell proceeds unsettled on cash acct). 2 positions remain: AIG(+0.55%)/GDDY(+0.02%). CB: daily 0.2%/weekly 0.8% (OK). MPC/PSX had MODERATE BUY (conf=2, rl=HOLD) but $0 investable. Universe=503.

## 2026-10-28T15:22:00Z
- Action   : SELL BRO
- Price    : $66.51
- Amount   : $89.64 | Shares: 1.347956
- RSI      : 26.84 | EMA: BEARISH | BB: BELOW_BAND
- RL       : HOLD conf=0.0 | null
- Stop     : trail_stop=$66.64 HIT | Entry: $67.48
- Strategy : normal | Exit: ATR trailing stop triggered
- Regime   : normal
- Reason   : ATR trailing stop — price $66.51 ≤ trail $66.64 (hrs_held ~23h). PnL: -1.44%

## 2026-10-28T15:22:00Z
- Action   : SELL HIG
- Price    : $131.98
- Amount   : $45.17 | Shares: 0.342289
- RSI      : 30.72 | EMA: BEARISH | BB: BELOW_BAND
- RL       : null conf=null | null
- Stop     : trail_stop=$132.81 HIT | Entry: $132.87
- Strategy : normal | Exit: ATR trailing stop triggered
- Regime   : normal
- Reason   : ATR trailing stop — price $131.98 ≤ trail $132.81 (hrs_held ~23h). PnL: -0.67%

## 2026-10-28T14:46:00Z (SUMMARY)
- SUMMARY: Market OPEN, in_window=true. Regime: normal. 4 positions held (BRO/-1.17%/trail $66.64, HIG/-0.02%/trail $132.81, AIG/+0.40%/trail $79.39, GDDY/+1.22%/trail $103.53). 0 SELLs: no triggers (trail stops not hit, no SELL signals on held positions, no TP). 0 BUYs: investable=$0.00 (BP=$50.00 − $50.00 buffer). CB: daily 0.0%/weekly 0.6% (OK). Trail stops: unchanged (no position ≥2.5% profit). Surge tracker: VRT/AEP count=1 (no confirmed intraday surge yet). BP=$50.00. Acct=$230.99. Universe=503.

## 2026-10-27T20:30:00Z (SUMMARY)
- SUMMARY: Market closed (16:12 EDT). 0 SELLs: no TP/stop/signal triggers. 0 BUYs: market closed. Regime: normal. 4 positions held (BRO/HIG/AIG/GDDY). CB: daily -0.3%/weekly -0.1% (OK). Trail stops: all unchanged (no position ≥2.5% profit). BP=$50.00. Acct=$232.55. Universe=503.

## 2026-10-27T19:21:34Z (SUMMARY)
- SUMMARY: Market open, in_window=true. Regime: normal. 3 positions held (BRO/HIG/AIG, ~2h 58min). 0 SELLs: no triggers (hrs_held<3 for sell rules b/c; no stops/TP hit). 1 BUY: GDDY $22.73 (RSI 28.2↑ BB-reversal RL-BOOST conf=2→3 STRONG-BUY, full investable). CB: daily +0.2%/weekly +0.0% (OK). BP=$50.00. Acct=$232.37. Universe=503.

## 2026-10-27T19:21:34Z
- Action   : BUY GDDY
- Price    : $105.47 (avg fill)
- Amount   : $22.73 | Shares: 0.215511
- RSI      : 28.2 | EMA: BEARISH | BB: BELOW_BAND
- RL       : BUY conf=0.928 | BOOST (conf 2→3)
- Stop     : $103.53 (ATR) | Target: $116.02
- Strategy : normal | Sell date: ATR/signal
- Regime   : normal
- Reason   : RSI oversold+stabilizing (30.1→28.2) | BB reversal returning from band | RL BOOST

## 2026-10-27T18:22:00Z
- SUMMARY: Market open, in_window=true. Regime: normal. 3 positions held (BRO/HIG/AIG, ~2h). 0 SELLs: no triggers (hrs_held<3, no sell signals for held tickers, no stops/TP hit). 0 BUYs: 8 RSI conf=2 candidates (META/BA/AMCR/CTVA/PSX/UHS/WM + HIG[held]) — investable $22.73×50%=$11.37 < $15 min. Surge: AME/DOV first sighted (count=1, need 2). CB: daily -0.0%/weekly +0.2% (OK). BP=$72.73. Acct=$232.02. Universe=503.

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

## 2026-10-29T14:38:32Z
- Action  : BUY ABNB
- Price   : $167.66 (est.)
- Amount  : $90.24 (~0.538 shares)
- RSI     : 29.9 (oversold+stabilizing 27.3→29.9) | EMA: BEARISH | BB: BELOW_BAND (reversal 0.09→0.16)
- RL      : BUY (conf=0.928)
- Stop    : $166.37 (ATR 0.77%) | Target: $184.43 (+10%)
- Reason  : RSI deeply oversold+stabilizing | BB reversal returning from lower band | RL BUY confirmation
- Order ID: 6ae35a68-ecd5-4ce1-b5ee-e83d3c4e70b5

## 2026-10-29T14:39:01Z
- Action  : BUY ELV
- Price   : $417.88 (est.)
- Amount  : $45.12 (~0.108 shares)
- RSI     : 28.6 (oversold+stabilizing) | EMA: BEARISH | BB: BELOW_BAND
- RL      : BUY (conf=0.928)
- Stop    : $414.29 (ATR 0.86%) | Target: $459.67 (+10%)
- Reason  : RSI deeply oversold | BB below band | RL BUY confirmation | second MODERATE position
- Order ID: 6ae35a85-23d6-4707-b309-bc30190fd9a3
