# momentum_based_quality_portfolio

The project aims to design a momentum-quality portfolio optimization model that could identify stocks showing both strong price momentum and solid financial health within the NASDAQ-100. The idea was to combine short-term performance signals with long-term business strength, balancing return potential with stability.

Using Python (with yfinance, pandas, and numpy), two years of historical price data were collected and cleaned. Each stock was ranked by its momentum, and then filtered using financial ratios like ROE, ROA and Debt-to-Equity to remove weak performers. The top ten stocks formed the portfolio, with weights assigned in proportion to their past returns.
A quarterly rebalancing system was built to update holdings and simulate real-world portfolio management. Performance was backtested over one year using metrics such as overall return, Sharpe ratio and maximum drawdown, while Excel was used to visualize capital growth and portfolio changes.

Techniques Used:

* Momentum and factor-based stock screening
* Portfolio weighting and quarterly rebalancing
* Backtesting and performance analytics (Sharpe ratio, volatility, drawdown)
* Data automation and visualization using Python and Excel

The portfolio delivered good returns during backtesting, showcasing how combining momentum with quality filters can enhance performance.
