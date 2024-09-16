# Stock Market Analyzer

This Python project analyzes stock market data, calculates various financial metrics, performs a simple portfolio optimization, and visualizes the results. It's designed to demonstrate skills in financial data analysis, optimization, and data visualization.

# The project outputs several key pieces of information:

- Annualized Returns and Volatility
- Sharpe Ratios
- Optimal Portfolio Weights
- Maximum Sharpe Ratio
- A visualization of the Risk-Return Trade-off

Let's explain each of these in detail:

- Annualized Returns and Volatility:
Annualized Return: This is the average yearly return of each stock. It's calculated by taking the average daily return and multiplying it by the number of trading days in a year (typically 252).
Annualized Volatility: This measures the standard deviation of returns, annualized. It represents the risk or uncertainty associated with the stock's returns.


- Sharpe Ratio:
This is a measure of risk-adjusted performance. It's calculated as (Return - Risk-Free Rate) / Volatility.
A higher Sharpe ratio indicates better risk-adjusted performance.
The risk-free rate in this project is assumed to be 2% (0.02).


- Optimal Portfolio Weights:
These are the percentages of each stock that should be held in the portfolio to maximize the Sharpe ratio.
The weights sum to 1 (or 100%).


- Maximum Sharpe Ratio:
This is the highest achievable Sharpe ratio given the stocks in the portfolio.


- Risk-Return Trade-off Visualization:
This scatter plot shows each stock's annualized return (y-axis) versus its annualized volatility (x-axis).
The color of each point represents its Sharpe ratio.
This visualizes the concept that higher returns often come with higher risk.

## Features

- Fetches historical stock data for multiple companies using yfinance
- Calculates daily returns, annualized returns, and volatility
- Computes Sharpe Ratio for risk-adjusted performance measurement
- Performs portfolio optimization to maximize Sharpe Ratio
- Visualizes risk-return trade-off of different stocks

## Requirements

- Python 3.7+
- yfinance
- pandas
- numpy
- matplotlib
- scipy

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/arjungopalcg/stock-market-analyzer.git

2. Navigate to the project directory:
   ```bash
   cd stock-market-analyzer

# Customization
You can modify the tickers list in the main() function to analyze different stocks. You can also adjust the start_date and end_date to change the time period of the analysis.

# Contributing
Contributions, issues, and feature requests are welcome. Feel free to check issues page if you want to contribute.


