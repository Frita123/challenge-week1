# challenge-week1
# Task 2: Quantitative Analysis of Stock Data using PyNance and TA-Lib

## Overview
This project performs quantitative analysis on stock price data using Python. The analysis combines **technical indicators** computed with **TA-Lib** and **financial metrics** using **PyNance / Pandas**.

The goal is to explore stock trends, compute portfolio metrics, and visualize performance over time.

---

## Features

### Data Preparation
- Load stock price data including `Open`, `High`, `Low`, `Close`, and `Volume`.
- Handle multiple tickers for portfolio-level analysis.
- Ensure data is sorted by date and missing values are handled.

### Technical Indicators (TA-Lib)
- **Simple Moving Average (SMA)**: 20-day and 50-day
- **Exponential Moving Average (EMA)**: 20-day
- **Relative Strength Index (RSI)**: 14-day
- **MACD**: 12/26/9 configuration

### Financial Metrics (PyNance / Pandas)
- Daily returns and cumulative returns
- Portfolio daily returns (equal-weighted)
- Annualized volatility
- Sharpe ratio
- Maximum drawdown

### Visualization
- Close price charts for individual stocks
- Trading volume charts
- Cumulative returns for portfolio
- Optional: overlay of technical indicators on price charts

---


