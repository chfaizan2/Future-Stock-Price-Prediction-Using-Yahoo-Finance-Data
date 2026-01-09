# Future-Stock-Price-Prediction-Using-Yahoo-Finance-Data
## Task Objective
To predict future stock prices of Apple Inc. (AAPL) using historical stock data and machine learning models.

To analyze stock price trends, volatility, and the impact of significant events on AAPL stock.

To implement and compare different predictive models and evaluate their performance.

## Dataset Used
Source: Yahoo Finance (yfinance library).

Stock: Apple Inc. (AAPL).

Date Range: January 1, 2020, to January 1, 2024.

Features Used:

Open, Close, High, Low, Volume

Derived features: Daily Return, Moving Averages (MA_10, MA_50), High-Low Difference

Target variable: Next_Close (next day's closing price)

## Models Applied
Linear Regression:

Used for baseline prediction.

Features: Open, High, Low, Volume, MA_10, MA_50, High_Low_Diff

Random Forest Regressor:

Ensemble method with 100 trees.

Same features as Linear Regression.

Moving Average Crossover Strategy:

Technical trading strategy using 20-day and 50-day moving averages.

Generates buy/sell signals based on crossover points.

## Key Results and Findings
Data Exploration:

AAPL stock price increased significantly from 2020 to 2024.

High correlation between Open and Close prices.

Volume spikes correspond with major price movements.

Technical Analysis:

Seasonal Decomposition: Showed trend, seasonality, and residual components.

Volatility: Rolling standard deviation indicated periods of high and low volatility.

Events Analysis: Stock splits and product launches visibly impacted stock prices.

Moving Average Crossover Strategy:

Generated clear buy/sell signals.

Strategy returns were visualized and analyzed cumulatively.

Model Performance:

Linear Regression:

Achieved moderate predictive accuracy.

R² score and error metrics were calculated.

Random Forest Regressor:

Outperformed Linear Regression in terms of lower error and higher R².

Captured non-linear patterns in stock data better.

Risk Metrics:

Sharpe Ratio: Measured risk-adjusted returns.

Sortino Ratio: Focused on downside risk.

Visualizations:

Multiple plots were created:

Price trends with moving averages

Event impacts (halving events, product launches)

Actual vs. predicted prices for both models

Conclusion
The Random Forest model provided better predictions than Linear Regression.

Technical indicators (moving averages, price ranges) were useful features.

Event-driven analysis highlighted the impact of corporate and market events on stock prices.

The moving average crossover strategy demonstrated practical trading signal generation.

