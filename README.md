📊 Bitcoin Market Sentiment vs Trader Performance
A Behavioral Finance Study Using Hyperliquid Trading Data
<p align="center"> <img src="https://readme-typing-svg.herokuapp.com?color=F7931A&size=22&center=true&vCenter=true&width=900&lines=Behavioral+Finance+in+Crypto+Markets;Does+Sentiment+Drive+Trading+Performance%3F;Hyperliquid+Data+Driven+Analysis" /> </p>
🧠 Executive Summary

Financial markets are not purely rational — they are emotion-driven systems.

This project investigates whether Bitcoin market sentiment (Fear & Greed Index) has a measurable impact on real trader performance using historical Hyperliquid trading data.

📌 Core Question:

Do traders perform better when the market is driven by fear, greed, or neutrality?

🎯 Objective

This project quantifies the relationship between market psychology and trading outcomes by analyzing:

💰 Profitability (Closed PnL)
🎯 Win rate across sentiment regimes
📦 Trade sizing behavior under emotional conditions
⚖️ Risk exposure shifts across market cycles
📁 Data Sources
1. Hyperliquid Trading Dataset

Granular execution-level trading data:

Account ID
Asset / Symbol
Execution Price
Position Size (USD / Tokens)
Side (BUY / SELL)
Closed PnL
Fees
Timestamp
2. Bitcoin Fear & Greed Index
<p align="center"> <img src="https://alternative.me/crypto/fear-and-greed-index.png" width="420"/> </p>
Sentiment	Score Range
🟥 Extreme Fear	0–24
🟧 Fear	25–44
⚪ Neutral	45–55
🟨 Greed	56–74
🟩 Extreme Greed	75–100
⚙️ Methodology
🔄 Data Engineering Pipeline
🧩 Feature Engineering
win_trade = Closed PnL > 0
Aggregated PnL per sentiment regime
Trade size distribution analysis
📊 Key Findings
💰 1. Profitability is Sentiment-Dependent
Sentiment	Performance
🟩 Extreme Greed	Highest total profits
🟨 Greed	Strong positive returns
⚪ Neutral	Mixed / inconsistent
🟥 Fear	Weak returns
🟧 Extreme Fear	Lowest performance

📌 Insight:
Market optimism significantly amplifies profitability.

🎯 2. Win Rate Varies Strongly with Emotion
🥇 Extreme Greed: ~46% (Highest)
🥶 Extreme Fear: ~37% (Lowest)

📌 Insight:
Trader decision accuracy improves in bullish emotional regimes.

📦 3. Trade Size Behavior Shifts Under Sentiment
Larger positions during Fear & Greed extremes
More conservative sizing during neutral phases
Greed regimes = higher efficiency per trade

📌 Insight:
Risk appetite is strongly sentiment-sensitive.

🧠 Core Insight

Market sentiment acts as a behavioral amplifier, not just a descriptive indicator.

It influences:

Decision quality
Risk appetite
Position sizing
Execution efficiency
📊 Business / Trading Implications

This analysis suggests sentiment can be used for:

📈 Strategy filtering (avoid low-performance regimes)
⚖️ Dynamic risk management
🎯 Entry timing optimization
🧠 Behavioral signal feature in ML models
🚀 Future Enhancements
🤖 Predict PnL using sentiment + market features (ML model)
📉 Add volatility, drawdown, and Sharpe ratio analysis
⚡ Build real-time sentiment-based trading signal system
📊 Extend to multi-asset crypto trading analysis
🛠️ Tech Stack
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
🔗 GitHub: https://github.com/karthik24092004
