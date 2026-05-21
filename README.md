# quant-wheel-strategy-backtest
The Wheel Strategy is an options trading strategy that combines selling cash-secured puts and covered calls to generate income from option premiums. In this project, I use historical SPY data and backtesting methods to evaluate whether the Wheel Strategy can outperform a passive buy-and-hold strategy over time.

# Project Overview
1. Implemented a Python-based backtesting framework for the Wheel Strategy
2. Simulated option premium collection and stock assignment cycles
3. Compared strategy performance against SPY buy-and-hold
4. Evaluated returns, volatility, Sharpe ratio, and drawdowns
5. Visualized portfolio growth and risk metrics over time

# Tools & Libraries
1. Python
2. pandas
3. numpy
4. matplotlib
5. yfinance
6. Jupyter Notebook

# Project Files
1. wheel_strategy_backtest.ipynb — Main notebook containing data processing, strategy simulation, and analysis
2. requirements.txt — Required Python dependencies

# Key Findings
The Wheel Strategy generated relatively stable premium income and reduced short-term volatility compared to buy-and-hold. However, during strong bull markets, the strategy often underperformed SPY due to capped upside from covered calls. The results highlight the tradeoff between income generation, downside protection, and long-term capital appreciation.
