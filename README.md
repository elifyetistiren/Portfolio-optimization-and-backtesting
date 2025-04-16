# 📊 Portfolio Analytics: Strategy Backtesting, Optimization & Risk Dashboard

This project simulates and compares multiple portfolio strategies using historical data from the top 20 S&P 500 companies by market capitalization. It evaluates performance using risk-adjusted return metrics and visualizes trends, drawdowns, and volatility.

---

## 🚀 Project Overview

**Goal:**  
To analyze portfolio performance, backtest investment strategies, and visualize risk-return profiles using real-world data and optimization techniques.

**Tools & Libraries:**  
`Python`, `Jupyter Notebook`, `yfinance`, `pandas`, `numpy`, `matplotlib`, `PyPortfolioOpt`

---

## 🧠 Key Concepts & Strategies

| Strategy             | Description |
|----------------------|-------------|
| 🎯 **Equal Weight**      | Assigns equal weight to each asset |
| ⚖️ **Risk Parity**        | Allocates based on inverse volatility |
| 📈 **Mean-Variance Opt.**| Optimizes Sharpe ratio using PyPortfolioOpt |
| 🧾 **Benchmark**          | S&P 500 index (^GSPC) as baseline |

---

## 📁 Dataset

- **Source:** [Yahoo Finance](https://finance.yahoo.com/)
- **Tickers Used:** Top 20 S&P 500 tickers (e.g., AAPL, MSFT, NVDA, AMZN...)
- **Timeframe:** 2010–2025
- **Data Type:** Adjusted Close Prices (auto-adjusted for splits/dividends)

---

## 📊 Visualizations

### ✅ Cumulative Returns – All Strategies

![cumulative returns](https://github.com/user-attachments/assets/8faf8f59-1aa4-4e93-9947-8570c117c5f5)

### 📉 Rolling Volatility (21-day)
![annual volatility](https://github.com/user-attachments/assets/2d0a7b5c-ce7c-4156-9a3f-fb3b526552c9)


### 🔻 Drawdown
![drawdown](https://github.com/user-attachments/assets/e6dd4980-f201-4fa3-8dd5-754b883b4193)


---

## 📈 Performance Metrics

| Strategy         | Return (Ann.) | Volatility (Ann.) | Sharpe Ratio |
|------------------|---------------|--------------------|--------------|
| Equal Weight     | ✔️ (calculated) | ✔️                  | ✔️            |
| Risk Parity      | ✔️              | ✔️                  | ✔️            |
| Mean-Variance Opt| ✔️              | ✔️                  | ✔️            |
| S&P 500          | ✔️              | ✔️                  | ✔️            |

> Note: All metrics annualized based on daily returns.

---

## 📦 Project Structure

```
Portfolio_Analytics_Project.ipynb     # Main notebook with analysis
README.md                             # Project overview
images/                               # Plots for GitHub rendering
```




---

## 🧑‍💻 Author

**Elif Yetistiren**  
_M.Sc. Information Management Systems | B.Sc. Finance_  
Data Analytics | Portfolio Optimization | Financial Risk Modeling
