# Backtesting a "Buy the Dip" Strategy

This project focuses on backtesting a "Buy the Dip" trading strategy across multiple financial indices. The goal is to assess how this strategy performs compared to a benchmark over a specified time period.

## Key Features:
**Strategy Definition**: The "Buy the Dip" strategy looks for days when the closing price is near the daily low, indicating a potential dip. Based on a set threshold, the system decides when to enter the market.

**Benchmark Comparison**: The project compares the strategy’s returns, drawdown, and other performance metrics with the benchmark (buy-and-hold) across different indices.

**Performance Metrics**: Metrics such as total return, Compound Annual Growth Rate (CAGR), drawdown, win rate, and time spent in the market are calculated to evaluate the strategy’s effectiveness.

**Backtesting Functionality**: A flexible function allows for testing the strategy on various indices by inputting their symbols, making it easy to compare results across multiple markets.

**Limitations**:
The backtest does not consider trading fees, FX rates, or other real-world factors that could impact the final balance.

## Technologies and Libraries Used:
This project leverages several Python libraries and technologies to implement the backtesting framework and perform data analysis:

**Python**: The primary programming language used for implementing the strategy and conducting analysis.

**NumPy**: A library for numerical operations, used for calculations involving arrays and mathematical functions.

**Matplotlib**: A plotting library used for visualising the results and performance metrics through charts and graphs.

**Jupyter Notebook**: An interactive environment that allows for easy experimentation, visualisation, and documentation of the code and results.
