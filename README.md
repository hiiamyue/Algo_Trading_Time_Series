# Algorithmic Trading & Time Series Analysis

This repository contains two projects analyzing ETFs using historical market data.

---

## Algorithmic Trading on SPTL

**Overview**  
Implements and evaluates three algorithmic trading strategies on the SPDR Portfolio Long Term Treasury ETF (SPTL) using historical data from 2014–2019.

**Strategies**  
- **Trend Following**: Uses moving averages to generate long/short signals.  
- **Mean Reversion**: Trades on short-term deviations assuming reversion to the mean.  
- **Autoregressive (AR) Model**: Predicts next-day prices and trades when moves exceed a threshold.

**Key Points**  
- Static leverage and cash account using the Effective Federal Funds Rate (EFFR) as risk-free rate.  
- Evaluated using cumulative/daily PnL, turnover, positions, and risk-adjusted metrics (Sharpe, Sortino, Max Drawdown, Calmar).

**Results**  
- Trend following is the most robust and profitable.  
- Mean reversion underperforms in trending markets.  
- AR model achieves moderate profitability.

---

## Time Series Analysis of SPY and SPTL

**Overview**  
Analyzes SPY and SPTL to explore trends, relationships, and statistical properties.

**Analyses**  
- **Moving averages and log returns**  
- **Correlation** between SPY and SPTL  
- **Gaussianity, stationarity, and cointegration tests**

**Findings**  
- SPY shows higher volatility and non-stationarity.  
- SPTL exhibits mean-reverting behavior.  
- Correlation and cointegration suggest potential for pairs trading and risk-adjusted portfolio strategies.
