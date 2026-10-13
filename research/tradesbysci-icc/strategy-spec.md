# SCI-ICC faithful strategy specification — DRAFT, not executable

## Documented concepts from the course
1. **Structure and regime** (Day 1): bull structure advances through higher highs/higher lows; bear structure through lower highs/lower lows; no trade in ambiguous consolidation.
2. **Indication** (Day 2): a meaningful swing high/low is broken and a new high/low forms, establishing *information about direction*, not an automatic entry. SCI favors 1-hour levels, sometimes 4-hour.
3. **Correction** (Day 3): after the indication, price can reverse temporarily and take liquidity; do not enter merely because the initial swing was breached.
4. **Continuation** (Days 4 and 6): inspect smaller-scale structure on 15-minute or 5-minute charts during the correction; watch for the structure to shift back toward the 1-hour directional indication, including the second directional move. SCI describes price action and structure, not proprietary indicator formulas.
5. **Location, targets and exits** (Days 4, 6, 13–14): use higher-timeframe swing levels for structural context/targets; for short examples, stop above relevant reaction lower high; for long examples, stop below relevant higher low.
6. **No-trade and context** (Days 5, 7, 9, 10, 12): higher-timeframe buyer/seller reaction levels, trend validity, range with no indication, and mixed evidence matter. Do not force entries.
7. **Timeframes** (Day 6): 4H/1H for structure; 15m/5m for correction-to-continuation entry detail. Don't mistake LTF noise for independent higher-timeframe thesis.
8. **Judgment and psychology** (Days 8, 11–13): patience, simplicity, avoiding revenge/FOMO trading and excessive leverage are core to the teaching.

## Explicit unknowns requiring chart-by-chart checks

- Unique, reproducible swing-point identification in noisy market data.
- Whether level breaks require closes or wicks and which exact threshold counts.
- Choice of 1H vs 4H when they conflict; equal-high/low handling.
- Correction duration/depth and exact end criteria.
- Intraday market session and news handling (NASDAQ/gold vs 24/7 crypto).
- Reaction zone boundaries, selection of competing highs/lows, stop buffer and TP selection.
- Partial exits, scaling, trailing stop and account-based sizing.
- Empirical fidelity of identifying original instructor chart examples.

These must not be silently invented and attributed to SCI. If an automated implementation requires an engineering assumption, label it as such with a configurable version and distinct evidence.

## Implementation and safety gates

- Maintain existing NORSTRADA engine and its paper-only boundary; don't enable real brokerage orders.
- Record every observed setup step (candidate swing, indication, correction, continuation), timestamp, timeframe and source rule; also log rejected signals and data staleness.
- Review examples for no-lookahead bias and then forward-test on BTC, ETH, SOL, XRP and DOGE with fees/spread/slippage.
- No performance claim based on SCI's self-reported earnings or retrospective selected examples.

**Source index:** [official lesson links](README.md). **Status:** all 14 captions accessed, Day 1 visuals reviewed, remaining visuals not yet reviewed.