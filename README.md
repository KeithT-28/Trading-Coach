# Trading-Coach
SPY Trading Coach (Educational Paper Trading)

A beginner-friendly, GitHub Pages-compatible web app for learning how two 15-minute equity strategies work:

• Trend-following pullbacks
• Breakouts and retests

It draws 20/50 EMAs, identifies confirmed swing highs/lows as candidate resistance/support, runs a simplified long-only historical simulation, and explains the latest trend and levels.

Important

• This is an educational prototype, not financial advice or a validated strategy.
• No live orders are placed.
• Demo data is synthetic and is not actual SPY history.
• For meaningful analysis, upload real SPY 15-minute OHLCV CSV data from a data provider.
• Backtest fills are simplified. The simulation uses one share, commission and slippage assumptions, and assumes the stop is hit first if a bar touches both stop and target.
• Do not interpret demo results as evidence of profitability.