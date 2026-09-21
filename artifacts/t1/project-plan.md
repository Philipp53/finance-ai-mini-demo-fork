# Project Plan — Finance AI Mini Demo

## Project Goal

Develop a clear and reproducible research workflow for comparing three familiar asset classes using illustrative ETF data:

- `SPY` — US equities
- `TLT` — long-term US Treasury bonds
- `GLD` — gold

The project starts with this written plan and will later use the same repository to design a bounded analysis task and organize a verifiable agent workflow.

## Available Data

`data/etf_snapshot.csv` contains one row per ETF with the following columns (see `data/data_dictionary.md`):

| Column | Unit | Meaning |
|---|---|---|
| `ticker` | — | Short identifier for the illustrative ETF |
| `asset_class` | — | Broad type of asset represented by the ETF |
| `expected_return_pct` | Percent per year | Illustrative annual return assumption |
| `volatility_pct` | Percent per year | Illustrative annual variability assumption |
| `max_drawdown_pct` | Percent | Illustrative largest peak-to-trough loss; negative values represent losses |
| `expense_ratio_pct` | Percent per year | Illustrative annual fund fee as a percentage of invested assets |

**Important:** This dataset is synthetic teaching data, not live or historical market observations.

## Expected Final Deliverable

A reproducible analysis that compares the three ETFs (SPY, TLT, GLD) on expected return, volatility, drawdown, and cost, and summarizes the trade-offs between the asset classes in a short written conclusion. The exact analysis steps and output format are planned in a later tutorial, not yet completed.

## Three Project Milestones

1. **Project setup (T1):** Write this initial project plan and save it with Git.
2. **Analysis design (later tutorial):** Define a bounded analysis task, choose the metrics and comparison approach, and document the steps.
3. **Verifiable execution:** Run the planned analysis, verify the results, and produce the final deliverable with an agent workflow.

## One Data Limitation

All numeric values in the dataset are synthetic teaching assumptions, not current quotations, verified historical estimates, or forecasts. The dataset also omits correlations, taxes, transaction costs, liquidity, currency exposure, and investor-specific constraints, so it must not be used as investment advice or as the basis for a real investment decision.

## Next Action

The plan is ready for review. The next step is for the student to review this file and save it with Git; later tutorials will design the analysis task on top of this setup.
