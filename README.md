# Stock Comparison Graph
This python code uses Yahoo Finance API (`yfinance`) paired with `matplotlib` to compare the performance of multiple stocks over a given period of time.
- This is done by pulling the historical price (HSP) data from `yfinance` and indexing the prices to 100. The close prices are then plotted on `matplotlib`.
# How To Use
Download `yfinance` by writing 'pip install' `yfinance` in your terminal.
Download `matplotlib` by writing 'pip install' `matplotlib` in your terminal.
# Changing Stocks
Navigate to line 04 and replace the `tickers` with your desired symbols - you may add more than 3 stocks.
# Changing Timeframe
Navigate to line 07 and change the `period` to any timeframe including:
- YTD
- 1D
- 5D
- 1Mo
- 3Mo
- 6Mo
- 1Y
- 2Y
- 5Y
- 10Y
- MAX
