📊 Bitcoin Market Sentiment vs Trader Performance
🧠 Project Overview

This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance using historical trading data from Hyperliquid. The goal is to identify whether market emotions influence profitability, trading behavior, and risk exposure.

📁 Datasets Used
1. Hyperliquid Historical Trading Data

Contains trade-level information such as:

Account ID
Coin / Symbol
Execution Price
Trade Size (Tokens & USD)
Side (BUY/SELL)
Closed PnL
Fees
Timestamp
2. Bitcoin Fear & Greed Index

Contains daily market sentiment:

Date
Value (0–100)
Classification:
Extreme Fear
Fear
Neutral
Greed
Extreme Greed
🎯 Objective
Merge trading data with sentiment index based on date
Analyze trader performance across different sentiment regimes
Identify patterns in:
Profitability (Closed PnL)
Win rate
Trade size exposure
Market behavior
🔧 Data Processing Steps
Converted timestamp to readable trade date
Merged trading data with sentiment index on date
Created derived metrics:
win_trade = Closed PnL > 0
Grouped analysis by sentiment classification
📊 Key Insights
💰 Profitability by Sentiment
Extreme Greed showed the highest total profits
Fear and Neutral zones had inconsistent performance
Extreme Fear showed lower overall returns
🎯 Win Rate Analysis
Highest win rate observed during Extreme Greed (~46%)
Lowest win rate observed during Extreme Fear (~37%)
Indicates sentiment strongly influences trading success
📦 Trade Size Exposure
Average trade sizes were higher in Fear and Greed regimes
Extreme Greed showed relatively lower average trade size but better efficiency
Suggests traders behave more cautiously in extreme conditions
📌 Conclusion

Market sentiment has a noticeable impact on trader performance.
Periods of Extreme Greed tend to produce better win rates and profitability, while Fear-driven markets show reduced performance and higher inconsistency.

This indicates that sentiment can be a useful feature for trading strategy design and risk management.

🛠️ Tools Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
📂 Repository Structure
├── sentiment_trading_analysis.ipynb
├── README.md
├── historical_data.csv (optional)
├── fear_greed_index.csv (optional)
🚀 Future Improvements
Add predictive model for PnL based on sentiment
Include volatility-based risk metrics
Build real-time sentiment trading signal system
👤 Author

Karthik Reddy
GitHub: https://github.com/karthik24092004
