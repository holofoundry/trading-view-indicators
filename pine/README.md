# Pine Script Layout

This directory is the home for all TradingView Pine Script work in the project.

## Recommended Structure

- `indicators/`
  - Finished scripts, grouped by strategy or signal family.
- `indicators/sessions/`
  - Session and market-hours indicators, including multi-market overlays.
- `indicators/liquidity/`
  - Liquidity zone, sweep, and stop-run style indicators.
- `libraries/`
  - Shared functions that multiple indicators use.
- `strategies/`
  - Trading strategies
- `templates/`
  - Starter files for new indicators.
- `experimental/`
  - Prototypes and in-progress ideas that are not ready for reuse.
- `archive/`
  - Deprecated scripts that should be kept for reference only.

## Suggested Indicator Buckets

Use subfolders under `indicators/` when the collection starts to grow:

- `trend/`
- `momentum/`
- `volatility/`
- `volume/`
- `market-structure/`
- `support-resistance/`
- `composite/`
- `sessions/`
- `liquidity/`

## Naming Convention

Prefer descriptive, lowercase, hyphenated filenames:

- `pine/indicators/trend/ema-ribbon.pine`
- `pine/indicators/momentum/rsi-divergence.pine`
- `pine/libraries/price-action-utils.pine`

Keep one primary script per file. If a script evolves significantly, move the older version into `archive/` rather than overwriting history.
