# kernal-vwap-pullback

VWAP pullback trading system (Pine Script).

- **Indicator edition (KVWAP):** EMA9/EMA21/VWAP with ATR(5) chop filter; pullback-setup diamonds, confirmed-entry triangles, alert conditions both directions, confirmed bars only. Verified working on live TradingView charts.
- **Strategy v6 (intraday):** longs-only, forced flat at 15:10 CT, fresh cross required, no overnight holds. Tested profit factor 1.77, 50% win rate, walk-forward holds.

Research verdicts: no profit target (targets cut PF to 1.02–1.41 — this is a right-tail system); no hard stop (signal exit + timed flat IS the risk management; a 200-tick stop would kill ~71% of signals).
