This project analyzes a five-stock banking portfolio using GARCH-based volatility forecasting on 5-minute intraday data. The objective is to study volatility behavior, risk-adjusted returns, and the impact of diversification using an equal-weighted portfolio.

Project Overview

The analysis uses 5-minute close-price data (7 Aug 2025 – 3 Oct 2025) for large-cap, mid-cap, and small-cap Indian banking stocks.
A GARCH(1,1) model is applied to estimate annualized volatility and understand risk dynamics.
Portfolio returns, drawdowns, Sharpe ratio, and Calmar ratio are computed to evaluate performance.

You can view all the calculated metrics in the image below (uploaded separately).

Key Insights

HDFC Bank provides stability due to its low volatility.

Federal Bank delivers the best risk-adjusted performance.

AU Bank and Equitas Bank show high returns but come with higher risk.

Bandhan Bank lies in the mid-range in both return and volatility.

The equal-weighted portfolio achieves lower overall volatility and higher Sharpe ratio due to diversification.

Methodology

Download and clean 5-minute intraday data

Compute log returns

Fit GARCH(1,1) models to estimate volatility

Construct equal-weighted portfolio

Evaluate returns, drawdown, Sharpe, Calmar, and volatility

Visualize results and trends

Work in Progress

EGARCH and GJR-GARCH (asymmetric volatility models)

Stochastic volatility and Heston model

Markowitz Portfolio Optimization

Correlation-driven weighting

Volatility trading strategies

Modular backtesting engine

How to Run
git clone https://github.com/yourusername/your-repo.git
cd your-repo
pip install -r requirements.txt
jupyter notebook

Tech Stack

Python

Pandas, NumPy

arch (GARCH models)

Jupyter Notebook

Matplotlib / Plotly
