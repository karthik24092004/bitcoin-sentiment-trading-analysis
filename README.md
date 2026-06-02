📊 Bitcoin Market Sentiment vs Trader Performance
🧠 Overview

This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance on Hyperliquid.

It evaluates whether market emotions influence:

Profitability
Win rate
Trading behavior
Risk exposure
🎯 Objective
Merge trading data with sentiment index
Study performance across sentiment regimes
Identify behavioral trading patterns
📁 Datasets
📌 Bitcoin Sentiment Dataset
Date
Classification → Fear / Greed / Neutral / Extreme Fear / Extreme Greed
📌 Hyperliquid Trading Dataset
Account ID
Symbol
Execution Price
Trade Size
Side (BUY / SELL)
Closed PnL
Leverage
Timestamp
⚙️ Methodology
🔹 Step 1: Data Preprocessing
Converted timestamp → date
Cleaned and standardized trading data
🔹 Step 2: Data Merging
Merged trading data with sentiment index on date
🔹 Step 3: Feature Engineering
win_trade = Closed PnL > 0
🔹 Step 4: Aggregation
Grouped by sentiment category
Computed:
Total PnL
Average PnL
Win rate
Trade size distribution
📊 Key Insights
💰 Profitability
Highest profits observed during Greed / Extreme Greed
Lower and unstable returns during Fear regimes
🎯 Win Rate
Highest win rate in Greed conditions
Lowest win rate in Extreme Fear
📦 Trading Behavior
Trade size increases during emotional extremes
More cautious behavior in Neutral markets
📌 Conclusion

Market sentiment has a clear and measurable impact on trading performance.

🟢 Greed → higher profitability and win rate
🔴 Fear → lower performance and inconsistency

Key Insight:
Sentiment is a strong behavioral signal in crypto trading.

🛠️ Tools Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
📂 Repository Structure
sentiment-trading-analysis/
│
├── sentiment_trading_analysis.ipynb
├── README.md
├── historical_data.csv
├── fear_greed_index.csv
👤 Author

Karthik Reddy
GitHub: https://github.com/karthik24092004
