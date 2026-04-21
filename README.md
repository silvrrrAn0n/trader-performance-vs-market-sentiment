# 📊 Trader Performance vs Market Sentiment Analysis

## 📌 Overview
This project analyzes how cryptocurrency trader performance varies under different market sentiment conditions using the Fear & Greed Index and historical trading data.

The goal is to uncover behavioral patterns, risk tendencies, and actionable insights that can improve trading strategies.

---

## 📂 Datasets Used

### 1. Bitcoin Market Sentiment Dataset
- Columns: Date, Classification (Fear, Greed, Extreme Fear, Extreme Greed, Neutral)

### 2. Historical Trader Data (Hyperliquid)
- account
- symbol
- execution price
- size / size_usd
- side (BUY/SELL)
- closed_pnl
- leverage
- time

---

## ⚙️ Data Processing Steps
- Data cleaning and handling missing values
- Timestamp conversion and date alignment
- Merging sentiment data with trader activity
- Feature engineering:
  - Win rate (`closed_pnl > 0`)
  - Normalized returns (`PnL / trade size`)

---

## 📊 Analysis Performed

### ✔ Exploratory Analysis
- PnL distribution across sentiment categories
- Trade frequency and volume analysis

### ✔ Performance Metrics
- Mean, Median PnL
- Win rate
- Trade size analysis

### ✔ Behavioral Analysis
- Buy vs Sell performance under different sentiments
- Risk-taking behavior (trade size & leverage)

### ✔ Advanced Analysis
- Risk-adjusted returns (normalized PnL)
- Time-series trend (rolling averages)
- Statistical testing (t-test)

---

## 📈 Key Visualizations
- Heatmap (PnL by Sentiment & Trade Side)
- Distribution plots (Histogram, Boxplot, Violin plot)
- Time-series trends (smoothed rolling averages)
- Trade behavior analysis (size, returns)

---

## 🔍 Key Insights

- 📉 **Fear markets favor BUY trades**
- 📈 **Greed markets favor SELL trades**
- ⚠️ Traders take **higher risks during Greed phases**
- 📊 Risk-adjusted returns are often **better in Fear conditions**
- 🧠 Evidence of **behavioral bias and emotional trading**

---

## 🚀 Strategy Implications

- Adopt **contrarian strategies**:
  - Buy during Fear
  - Sell during Greed
- Avoid excessive leverage in high-greed markets
- Focus on **risk-adjusted returns**, not just absolute profit

---

## 🛠️ Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

---

## 📁 Project Structure
