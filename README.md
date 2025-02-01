# Simulating Stock Returns Using Probability Distributions
# Project Overview
This project simulates stock returns using Monte Carlo methods and probability distributions.
It models daily stock price movements based on historical return distributions and evaluates
future price trends using stochastic processes.
# Features
- Fetch real stock market data from Yahoo Finance.
- Estimate expected return and volatility using historical data.
- Generate random stock price movements using a normal distribution.
- Simulate thousands of stock price paths over a given time horizon.
- Visualize the simulated price paths using Matplotlib.
- Analyze portfolio risk and return using statistical metrics.
# Installation & Requirements
To run this project, install the required Python libraries:
pip install numpy pandas matplotlib yfinance
# How It Works
1. Fetch real stock data
2. Estimate expected return and volatility
3. Generate simulated stock returns using a normal distribution
4. Compute stock price paths using the Geometric Brownian Motion (GBM) model
5. Visualize the simulated stock price paths
# Applications
- Quantitative Trading Strategies - Simulating potential price movements before executing trades.
- Portfolio Optimization - Assessing risk-adjusted expected returns for investment decisions.
- Options Pricing - Using Monte Carlo methods to estimate derivative prices.
