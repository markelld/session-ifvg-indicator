# Session Sweep IFVG Retest Model

TradingView Pine Script indicator for a 1-minute session-based model.

## Features
- Asia, London, and Premarket session highs/lows
- New York entry window
- Buyside / sellside liquidity sweeps
- Inverted FVG retest entries
- Entry, stop, and target visuals

## Logic
### Long
- Sellside liquidity sweep
- Bearish FVG inverts bullish
- Price retests IFVG
- Stop below last swing low
- Target opposing session high

### Short
- Buyside liquidity sweep
- Bullish FVG inverts bearish
- Price retests IFVG
- Stop above last swing high
- Target opposing session low

## Files
- `pine/indicator_v1.pine` - main indicator
- `docs/model-rules.md` - strategy rules