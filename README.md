# VaR_and_CVaR_Analysis
Multi-method portfolio VaR and CVaR analysis using parametric, historical, and EWMA risk models in Python.

This project looks at different ways to estimate Value-at-Risk (VaR) and Conditional VaR (CVaR) for a multi-asset portfolio. The goal was to see how risk estimates change depending on the model assumptions and how each method behaves during normal periods versus stress events.

## What the project does

- Builds a portfolio return series from asset price data
- Estimates volatility using standard and EWMA approaches
- Computes VaR using multiple methods
- Calculates CVaR to measure tail losses
- Compares results across models and time periods

## VaR methods included

**Parametric (Normal) VaR**
- Assumes returns are normally distributed
- Uses portfolio mean and volatility

**EWMA VaR**
- Uses exponentially weighted volatility
- Places more weight on recent observations

**Historical Simulation VaR**
- Uses the empirical return distribution
- Does not rely on distribution assumptions

**Conditional VaR (CVaR)**
- Measures the average loss beyond the VaR cutoff
- Provides a clearer picture of tail risk

## Main concepts covered

- Portfolio return aggregation
- Volatility modeling
- Tail risk estimation
- Model comparison
- Basic VaR backtesting
