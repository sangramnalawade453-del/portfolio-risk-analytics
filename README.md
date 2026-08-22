# Portfolio & Risk Management Analytics

Quantitative analysis of a 10-stock equity portfolio (2001–2025), covering stock selection, risk-adjusted performance, Value-at-Risk modeling, Monte Carlo simulation, and Modern Portfolio Theory optimization.

## Overview
This project builds an end-to-end portfolio analytics framework — from raw price data to an optimized, risk-assessed portfolio — using Python. It benchmarks an equal-weighted 10-stock portfolio against the S&P 500, quantifies downside risk using four independent VaR/CVaR methodologies, and derives optimal allocations using Modern Portfolio Theory.

## Key Components
- **Stock Selection & Metrics**: Sharpe, Sortino, Treynor, Jensen's Alpha, Beta, Max Drawdown across 10 stocks (2001–2025)
- **Portfolio Construction**: Equal-weighted portfolio vs S&P 500 benchmark
- **Risk Analysis**: Historical & Parametric VaR/CVaR (95%/99%), skewness/kurtosis, correlation regimes (2008 Crisis, COVID)
- **Monte Carlo Simulation**: 20,000 simulated 1-year portfolio paths using two methods — Pure GBM (log returns) and GBM + Bootstrap (preserves fat tails/skew)
- **Portfolio Optimization (MPT)**: Efficient Frontier, Minimum Variance Portfolio, Maximum Sharpe Ratio Portfolio (solved via `scipy.optimize` SLSQP)
- **Risk Dashboard**: Consolidated VaR/CVaR comparison (4 methods × 2 confidence levels) across 3 portfolio strategies

## Tools & Libraries
`Python` · `pandas` · `numpy` · `scipy` · `matplotlib` · `seaborn` · `yfinance`

## Sample Visuals
<img width="1349" height="418" alt="Screenshot 2026-08-23 at 12 13 28 AM" src="https://github.com/user-attachments/assets/2cd642b8-a3c5-4bd2-b88b-915ac59d525c" />
<img width="1349" height="570" alt="Screenshot 2026-08-23 at 12 15 48 AM" src="https://github.com/user-attachments/assets/c87c521a-6a3c-4eac-8c72-c76a1cb12f20" />
<img width="1376" height="570" alt="Screenshot 2026-08-23 at 12 24 46 AM" src="https://github.com/user-attachments/assets/58eae8d3-94d4-4cdd-ace2-f51f05a8535d" />

## Notebook
[View the full analysis](./Portfolio_Risk_Analytics_SN.ipynb)

---
**Author**: Sangram Nalawade | [LinkedIn](https://linkedin.com/in/sangram-nalawade)
