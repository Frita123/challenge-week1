# challenge-week1
# Task 3: Correlation Between News Sentiment and Stock Movements

## Overview
This task analyzes the relationship between news sentiment and stock price movements for six major technology companies: AAPL, AMZN, GOOG, META, MSFT, and NVDA. The goal is to understand how daily news sentiment affects stock returns.

## Methodology
1. **Data Preparation**
   - Convert news headlines into sentiment scores using the VADER sentiment analyzer.
   - Compute daily percentage returns for each stock using closing prices.

2. **Date Alignment**
   - Align news and stock datasets by date to match each news item to the corresponding trading day.

3. **Correlation Analysis**
   - Calculate the Pearson correlation coefficient between daily sentiment scores and stock daily returns.

4. **Visualization**
   - Generate scatter plots of daily sentiment vs. daily returns for each stock.

## Tools & Libraries
- Python 3.x
- Pandas
- Numpy
- Matplotlib
- NLTK (VADER Sentiment Analyzer)

## Output
- Correlation table showing the correlation between sentiment and returns for each stock.
- Scatter plots for visual inspection of sentiment vs returns.

## Usage
1. Place all stock CSV files and the news dataset in the `data/` folder.
2. Run the notebook `task-3.ipynb` to compute correlations and generate plots.
3. Examine `correlations_df` for numeric results and plots for patterns.

## Notes
- Only overlapping dates between news and stock data are used.
- Missing or invalid dates are removed automatically.
- The analysis can be extended to include lagged correlations to study predictive effects of news sentiment.
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


# Challenge Week 1 - Financial News EDA

## Overview
This repository contains the work for **Task 1: Git and GitHub**, which focuses on:

- Setting up a Python environment for data analysis
- Using Git version control for code management
- Performing **Exploratory Data Analysis (EDA)** on a financial news dataset
- Demonstrating skills in descriptive statistics, time series analysis, and topic modeling

The dataset consists of financial news articles, including the following columns:

- `headline`: Title of the news article
- `url`: Direct link to the article
- `publisher`: Author or creator of the article
- `date`: Publication date and time (including timezone)
- `stock`: Stock ticker symbol (e.g., AAPL for Apple)

---

## Repository Structure

