# Quantitative-Analysis-of-Apple-Stock-2020-2025
## Project Summary:
This project examines Apple’s stock (AAPL) over the recent five-year period from 2020 to 2025. It focuses on the relationships among price, trading volume, and key technical indicators. Using daily historical data sourced from Kaggle, the study analyzes how these variables interact and evaluates their potential to inform traders’ buy and sell decisions.
## Research Questions
1. Do Apple’s stock prices follow identical and exploitable patterns over the 2020–2025 period?
2. How are stock price and trading volume related? Does price help explain or predict changes in volume?
3. Can we use technical indicators, such as moving averages (SMA 50, SMA 200) and Volume Weighted Average Price (VWAP), to identify trends or shifts in Apple’s stock?
4. What is the “fair value”?
## Data and Scope
- Data Source: Daily historical stock data for Apple (AAPL) obtained from Kaggle (1980–2025).
- Study Period: Filtered to a 5-year window (January 2020–January 2025) to focus on recent market behavior and modern trading conditions.
- Variables of Interest: Open, High, Low, Close, Adjusted Close, and Volume.
## Data Preparation
- Cleaned and standardized column names.
- Converted date fields to proper datetime format for time-series analysis.
- Fixed missing or inconsistent values for a reliable dataset.
## Technical Indicator Construction
### Simple Moving Averages (SMA 50 and SMA 200):
- SMA 50 used as a short-term trend indicator.
- SMA 200 used as a long-term trend indicator.
- The interaction of these two averages (Golden and Death Crosses) acts as a signal in the stock.
### Volume Weighted Average Price (VWAP):
- Calculated to show the “fair value,” a benchmark that weights prices by how often they are traded.
- Compares the stock’s current price to its typical price based on recent trading volume.
## Analytical Approach
- Descriptive and Correlation Analysis: To explore how price-related variables (Open, High, Low, Close, Adjusted Close) move together and how they relate to volume.
- Simple Linear Regression (Volume ~ Close): To check if daily closing prices help explain or predict trading volume.
- Trend and Signal Analysis: Using SMA crossovers and VWAP to spot possible buy/sell signals and assess Apple’s value over the study period.
