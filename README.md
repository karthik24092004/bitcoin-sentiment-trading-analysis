:

📊 Bitcoin Market Sentiment vs Trader Performance

A data-driven analysis of how Bitcoin market sentiment influences trader profitability and behavior using Hyperliquid trading data and the Fear & Greed Index.

🧠 Overview

This project explores the relationship between market sentiment and trader performance in the cryptocurrency market.

It investigates whether emotional states like Fear and Greed impact:

Profitability
Win rate
Trade sizing behavior
Risk exposure

By merging trading data with sentiment indicators, this analysis provides insights into behavioral finance in crypto markets.

🎯 Objective
Merge Hyperliquid trading data with Bitcoin Fear & Greed Index
Analyze trader performance across sentiment regimes
Identify behavioral patterns driven by market emotions
Evaluate impact on:
Closed PnL
Win rate
Trade size
Risk behavior
📁 Datasets
1. Hyperliquid Trading Data

Contains trade-level execution data:

Account ID
Coin / Symbol
Execution Price
Trade Size (Tokens & USD)
Side (BUY / SELL)
Closed PnL
Fees
Timestamp
2. Bitcoin Fear & Greed Index

Daily sentiment classification of the crypto market:

Sentiment	Range
Extreme Fear	0–24
Fear	25–44
Neutral	45–55
Greed	56–74
Extreme Greed	75–100
⚙️ Data Processing
Converted timestamp → trade date
Merged trading dataset with sentiment index
Created feature: win_trade = Closed PnL > 0
Aggregated metrics by sentiment category
📊 Key Insights
💰 Profitability
Extreme Greed generated the highest total profits
Fear & Neutral regimes showed inconsistent returns
Extreme Fear had the weakest performance
🎯 Win Rate
Highest win rate: Extreme Greed (~46%)
Lowest win rate: Extreme Fear (~37%)
Clear indication that sentiment affects execution quality
📦 Trade Size Behavior
Higher trade sizes observed in Fear and Greed phases
Extreme Greed showed better efficiency despite smaller average trades
📌 Conclusion

Market sentiment has a measurable impact on trading performance.

Greed-driven markets → higher profitability & win rates
Fear-driven markets → lower performance & inconsistency
Key Insight:

Sentiment can be a valuable feature for trading strategies and risk management systems.

🛠️ Tech Stack
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
📂 Repository Structure
├── sentiment_trading_analysis.ipynb
├── README.md
├── historical_data.csv
├── fear_greed_index.csv
🚀 Future Improvements
Build ML model to predict PnL using sentiment
Add volatility and risk-adjusted metrics (Sharpe ratio, drawdown)
Develop real-time sentiment-based trading signal system
Extend analysis to multi-asset crypto markets
👤 Author

Karthik Reddy
GitHub: https://github.com/karthik24092004
