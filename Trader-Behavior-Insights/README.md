# Trader Behavior Insights – Sentiment-Based Trading Analysis

This project is about analyzing how trader behavior changes based on market sentiment like Fear, Greed, etc.

## 📁 Datasets Used

1. **Hyperliquid Trader Data** – includes trade details like account, execution price, size, side (BUY/SELL), PnL, fee, etc.
2. **Fear & Greed Index Data** – gives daily market sentiment (like Extreme Fear, Fear, Neutral, Greed, Extreme Greed)

---

## 🔍 What I tried to understand

- Which sentiment leads to more profit for traders?
- Is BUY better or SELL during different market moods?
- Do bigger trades give better results?
- Does trader behavior really change based on sentiment?

---

## 📊 Graphs Created

- Average PnL per Sentiment (Bar Chart)
- PnL Trend Over Time (Monthly & Yearly Line Plot)
- PnL Distribution by Side & Sentiment (Box Plot)
- Trade Proportion by Sentiment (Pie Chart)
- Heatmap: Side vs Sentiment vs Avg PnL
- Volume of Trades by Sentiment
- PnL Volatility (Standard Deviation)

---

## 💡 Key Insights

- Most trades happen during Fear, but Extreme Greed gives higher average profit.
- Side (BUY/SELL) performance depends heavily on sentiment.
- Larger trades come with higher risk.
- Only a few accounts are consistently profitable — possibly experienced traders or bots.

---

## 📂 Project Folder Structure

| File | Description |
|------|-------------|
| `trader_analysis.ipynb` | Main analysis notebook |
| `README.md` | This file – project summary |

---

## 🛠 Tools Used

- Python
- Pandas, Seaborn, Matplotlib
- Jupyter Notebook

---

## 🧠 Final Note

This project helped me understand how human emotions and sentiment affect trading behavior.  
It was a great learning experience turning raw data into actionable insights.

