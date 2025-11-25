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
