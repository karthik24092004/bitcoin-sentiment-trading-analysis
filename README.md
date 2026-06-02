<div align="center">

# 📊 Primetrade.ai Assignment  
### Bitcoin Sentiment vs Trader Performance Analysis

> A data analysis project exploring the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance using Hyperliquid historical trading data.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

</div>

---

## 📌 Assignment Objective

This project was completed as part of the **Primetrade.ai Data Science Hiring Assignment**.

The objective was to:
- Analyze Bitcoin market sentiment using Fear & Greed Index  
- Study trader performance using Hyperliquid historical trading data  
- Identify patterns between sentiment and profitability  
- Extract actionable insights for trading behavior  

---

## 📁 Datasets Provided

### 1. Hyperliquid Historical Trading Data
Contains execution-level trading information:
- Account ID  
- Coin / Asset  
- Execution Price  
- Trade Size (USD & Tokens)  
- Side (BUY/SELL)  
- Closed PnL  
- Timestamp  

---

### 2. Bitcoin Fear & Greed Index
Daily sentiment classification of the crypto market:
- Extreme Fear  
- Fear  
- Neutral  
- Greed  
- Extreme Greed  

---

## ⚙️ Methodology

1. Loaded and explored both datasets  
2. Converted timestamps into trade dates  
3. Merged datasets using date as the key  
4. Engineered feature:
   - `win_trade = Closed PnL > 0`  
5. Performed grouped analysis based on sentiment classification  

---

## 📊 Analysis Performed

- Trader profitability across sentiment regimes  
- Win rate comparison by sentiment class  
- Trade size and exposure analysis  
- Aggregated performance across accounts  

---

## 📈 Key Insights

### 💰 Profitability
- Higher total profits observed during **Greed and Extreme Greed phases**
- Lower consistency during Fear-driven markets  

---

### 🎯 Win Rate
- **Extreme Greed → highest win rate (~46%)**
- **Extreme Fear → lowest win rate (~37%)**

---

### 📦 Trading Behavior
- Traders take larger positions in emotional market conditions  
- Sentiment significantly influences risk-taking behavior  

---

## 📌 Conclusion

The analysis shows that **market sentiment has a measurable impact on trader performance**.

- Greed phases tend to improve profitability  
- Fear phases reduce trading accuracy and consistency  
- Sentiment can be used as an important feature in trading strategy design  

---

## 🛠️ Tech Stack

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 📁 Repository Structure

```text
sentiment_trading_analysis.ipynb
README.md
historical_data.csv
fear_greed_index.csv
👤 Author

Karthik Reddy
GitHub: https://github.com/karthik24092004

📌 Submission Note

This repository contains the solution for the Primetrade.ai Data Science Hiring Assignment.
