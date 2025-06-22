# 📈 Algo Trading Strategy Backtester

This project implements a simple **Moving Average Crossover Strategy** to backtest trading signals on historical stock data using Python.

## 🔧 Features
- SMA(20) / SMA(50) crossover signals
- Strategy vs Market return comparison
- Sharpe Ratio & Maximum Drawdown calculation
- Visualization of cumulative returns

## 📚 Requirements
- `yfinance`
- `pandas`
- `matplotlib`
- `numpy`

Install dependencies with:
```bash
pip install yfinance pandas matplotlib numpy
```

## 📊 How It Works
- **Buy** when 20-day SMA > 50-day SMA
- **Sell** when 20-day SMA < 50-day SMA
- Calculate daily returns based on signal
- Evaluate strategy performance vs. market

## 📈 Output
- Line chart of cumulative returns
- Risk metrics:
  - Sharpe Ratio
  - Max Drawdown
