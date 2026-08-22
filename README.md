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
*(add 2-3 screenshots here, e.g. efficient frontier, fan chart, risk dashboard table)*

## Notebook
[View the full analysis](./Portfolio_Risk_Analytics_SN.ipynb)

---
**Author**: Sangram Nalawade | [LinkedIn](https://linkedin.com/in/sangram-nalawade)
