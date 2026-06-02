📊 Bitcoin Market Sentiment vs Trader Performance
A Quantitative Analysis of Behavioral Bias in Crypto Trading
🧠 Overview

This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance on Hyperliquid.

The objective is to understand whether market emotions influence profitability, risk behavior, and execution quality in real trading environments.

🎯 Objective

This study investigates how trader behavior changes under different market sentiment regimes by analyzing:

💰 Profitability (Closed PnL)
🎯 Win rate distribution
📦 Trade size and exposure behavior
⚖️ Risk-taking patterns under emotional markets
📁 Datasets
📌 1. Bitcoin Market Sentiment Dataset
Date
Classification (Fear / Greed / Neutral / Extreme Fear / Extreme Greed)
📌 2. Hyperliquid Trader Dataset

Includes trade-level execution data:

Account ID
Symbol
Execution Price
Size (Position / Tokens / USD)
Side (BUY / SELL)
Closed PnL
Leverage
Timestamp
Trade event metadata
⚙️ Methodology
🔄 Data Processing Pipeline
Converted timestamp → trading date
Standardized and cleaned trading records
Merged datasets on date
Engineered features:
win_trade = Closed PnL > 0
Trade-level aggregation metrics
🧩 Analytical Framework

The analysis is structured across three dimensions:

Performance Analysis
Profitability across sentiment regimes
Win rate comparison
Behavioral Analysis
Trade size variation
Position exposure changes
Risk Analysis
Leverage usage patterns
Behavior under extreme sentiment conditions
📊 Key Insights
💰 1. Profitability is Strongly Sentiment-Dependent
Extreme Greed → Highest profitability
Greed → Consistently positive performance
Fear / Extreme Fear → Lower and unstable returns

📌 Insight:
Risk-on sentiment phases significantly improve trading outcomes.

🎯 2. Win Rate Varies Across Market Psychology
Highest win rate observed in Greed / Extreme Greed regimes
Lowest win rate during Extreme Fear phases

📌 Insight:
Execution accuracy improves when market sentiment is positive.

📦 3. Trade Size & Risk Exposure Behavior
Higher trade sizes observed during Fear and Greed regimes
Reduced activity in neutral environments
Extreme sentiment leads to more aggressive positioning

📌 Insight:
Trader risk appetite is directly influenced by market emotion.

⚠️ 4. Behavioral Observation

Market sentiment not only affects outcomes but also:

Decision confidence
Trade frequency
Position sizing discipline

📌 Insight:
Trading behavior is emotionally adaptive rather than purely rational.

🧠 Core Insight

Market sentiment acts as a behavioral driver, influencing both decision-making and execution quality in crypto trading environments.

📈 Conclusion

The analysis confirms a clear relationship between market psychology and trading performance:

Sentiment Regime	Trader Behavior
🟢 Greed	High confidence, better performance
🔴 Fear	Defensive behavior, inconsistent returns
⚪ Neutral	Mixed and indecisive trading patterns
🚀 Potential Applications

This analysis can be extended into:

📊 Sentiment-based trading strategies
⚖️ Dynamic risk management systems
🤖 ML-based PnL prediction models
⚡ Real-time trading signal generation
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
