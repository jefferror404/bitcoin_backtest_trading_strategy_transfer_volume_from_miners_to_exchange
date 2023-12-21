# bitcoin_backtest_trading_strategy_transfer_volume_from_miners_to_exchange
This is a sharing and demonstration of how to utilize the backtesting.py library to carry out a backtest on a bitcoin program trading strategy. 
Disclaimer: This is not an investment advise. 

I will share how I utilize an on-chain data metric "transfer volume from miners to exchange" to come up with a "short-only" trading strategy using a simple zscore idea and carry out the backtest.

Note that data is not provided.

The sharing includes how to use the backtesting.py to 
i) write a strategy for backtest
ii) optimize the parameters (e.g. zscore, RSI) 
iii) plot the results and trade details for further analysis

Here is a brief summary of the backtest results:
Backtest period: 2021-01-01 to 2023-11-22
Sharpe ratio: 1.42
Max drawdown: -6.92%
Strategy return: 53.3% 
Buy & hold return: 26.1%
Win rate: 60.8%
Number of trades: 314 


