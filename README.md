# Modern-Portfolio-Theory-Optimization
📌 Project Overview

This project applies Modern Portfolio Theory (MPT) to construct and analyze optimal portfolios using real stock market data.
By simulating thousands of random portfolios, the project identifies the Minimum Variance Portfolio, Maximum Sharpe Ratio Portfolio, and visualizes the Efficient Frontier.

The analysis helps investors understand the risk–return tradeoff and make data-driven portfolio allocation decisions.

🎯 Objectives

Generate and evaluate 5,000 random portfolios

Calculate annualized return and volatility

Identify optimal portfolios based on:

Minimum risk

Maximum risk-adjusted return (Sharpe Ratio)

Visualize the Efficient Frontier

🛠 Tech Stack

Python

NumPy

Pandas

yFinance

Matplotlib

Quantitative Portfolio Theory

📊 Portfolio Details

Assets: AAPL, MSFT, GOOGL

Data Source: Yahoo Finance

Start Date: 2022-01-01

Returns: Daily returns, annualized

Risk-Free Rate: Assumed 0 (for Sharpe Ratio)

📐 Financial Concepts Used

Modern Portfolio Theory (Markowitz)

Expected Return

Covariance Matrix

Portfolio Volatility

Sharpe Ratio

Efficient Frontier

▶ How the Model Works

Download historical stock prices

Compute daily returns

Estimate mean returns and covariance matrix

Randomly generate portfolio weights

Calculate:

Annualized Return

Annualized Risk (Volatility)

Sharpe Ratio

Identify optimal portfolios

Plot risk–return space and efficient frontier
