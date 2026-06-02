<div align="center">

# 📊 Bitcoin Sentiment vs Trader Performance Analysis

### *Do market emotions drive trading profits?*

> A data-driven study exploring how Bitcoin Fear & Greed sentiment influences trader behavior and profitability using real Hyperliquid trading data.

🌐 *Built with Python, Pandas & real crypto market data*

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Visualization-11557C?style=for-the-badge)

</div>

---

## 🌟 Why This Project?

Crypto markets are driven by emotion — not logic.

Fear leads to panic selling.  
Greed leads to over-leveraged buying.

This project investigates:

> **Can we quantify how market sentiment affects trader profitability?**

---

## 📁 Datasets Used

### 📊 Hyperliquid Trading Data
- Account-level trade history
- Execution price & position size
- Closed PnL (profit/loss)
- Trade direction (BUY/SELL)
- Timestamp-level execution data

### 🧠 Bitcoin Fear & Greed Index
- Daily sentiment score (0–100)
- Classified into:
  - Extreme Fear
  - Fear
  - Neutral
  - Greed
  - Extreme Greed

---

## ⚙️ Workflow

```text
📥 Data Collection
        ↓
🧹 Data Cleaning & Timestamp Processing
        ↓
🔗 Merge Trading Data + Sentiment Index
        ↓
📊 Group Analysis by Sentiment Class
        ↓
📈 Profitability & Win Rate Evaluation
        ↓
💡 Insight Extraction
📊 Key Findings
💰 Profitability vs Sentiment
Highest total profits observed during Greed phases
Extreme Fear shows lower trading efficiency
🎯 Win Rate Analysis
🟢 Extreme Greed → ~46% win rate (highest)
🔴 Extreme Fear → ~37% win rate (lowest)
📦 Trading Behavior Patterns
Traders take larger positions during emotional extremes
Market sentiment strongly influences risk appetite
Behavioral bias is clearly visible in execution data
📌 Key Insight

📉 Markets are not just mathematical systems — they are emotional systems.

✔ Greed improves confidence but increases risk
✔ Fear reduces participation but also reduces accuracy
✔ Sentiment is a powerful trading signal

🛠️ Tech Stack
Tool	Purpose
🐍 Python	Core analysis
📦 Pandas	Data processing
🔢 NumPy	Numerical computation
📊 Matplotlib	Visualization
📈 Seaborn	Statistical plots
📓 Jupyter Notebook	Interactive analysis
📁 Project Structure
📦 Bitcoin-Sentiment-Analysis
 ┣ 📜 sentiment_trading_analysis.ipynb
 ┣ 📜 README.md
 ┣ 📊 historical_data.csv
 ┣ 📊 fear_greed_index.csv
🚀 Future Improvements
Predict trader profitability using sentiment signals
Build real-time sentiment trading dashboard
Add risk-adjusted performance metrics (Sharpe Ratio)
Extend analysis to multiple crypto assets
👤 Author

Karthik Reddy
GitHub: https://github.com/karthik24092004

<div align="center">
⭐ If you like this project, consider exploring more of my work
</div>
