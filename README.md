# GARCH modeling & volatility-based Strategy

This repository outlines a comprehensive approach to analyzing the time series of SPY (S&P 500 ETF) returns over a 6-year period (2019-2024) and implementing a volatility-based trading strategy based upon regime classification.

## Overview

In the 1st part the analysis begins with data preparation, calculating log returns, and conducting statistical tests for justifying the use of a **GARCH(p,q)** model based on the goodness of fit. Afterwards the model get optimized and it is used to forecast the volatility. 

In the 2nd part, a **regime classification** inform position sizing based on 4 volatility groups (**Low, Normal, High and Extreme-Crisis**) for the trading strategy. Key performance metrics such as total return, annual volatility, Sharpe ratio, and maximum drawdown are calculated to evaluate the strategy against a buy-and-hold approach. Visualizations illustrating equity growth and volatility trends throughout the process.

## Contents

- **Data Preparation**: Downloading SPY price data and calculating log returns.
- **Statistical Analysis**: Normality, stationarity and fat tails tests.
- **Volatility Modeling**: GARCH model for volatility assessment.
- **Volatility Optimization**: Based upon different mean models, volatility models and distributions.

![output_1](https://github.com/user-attachments/assets/bdb0f1f6-b048-476f-96f1-309662f5728a)

#
- **Regime Classification**: Identifying market conditions and grouping volatility for strategy implementation.
- **Position sizing**: Based on the forecast's of the identified regime.
- **Visualizations**: Graphical representations of both strategy's and benchmark's equity curves.
- **Performance Metrics**: Evaluating strategy performance against buy and hold benchmark.

![output_2](https://github.com/user-attachments/assets/8b6e3b92-44d1-457b-a0ae-901dde5222d4)

