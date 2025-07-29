# 📈 Quant Trading Strategies – Ceiron Dushyanthan

This repository contains end-to-end implementations of quantitative trading strategies developed in Python. Each project includes full signal logic, backtesting, and performance analysis — designed to build real-world quant skills from the ground up.

---

## ✅ Completed Projects

### 1️⃣ Buy-and-Hold Benchmark Strategy

**Goal**: Track the growth of a $10,000 investment in a single stock (e.g., AAPL) as a baseline benchmark.

**What It Includes**:
- Equity curve
- Daily and cumulative returns
- Sharpe Ratio, Max Drawdown, CAGR

**Tech Used**: `pandas`, `matplotlib`, `yfinance`

---

### 2️⃣ Mean Reversion Strategy (Z-Score Based)

**Goal**: Trade a stock based on its deviation from its recent average price using z-score logic.

**Strategy Logic**:
- Go long when z-score < -1
- Go flat when z-score > 0
- (Optional) Short when z-score > 1

**Highlights**:
- Rolling mean & std
- Z-score signal generation
- Backtest engine and equity curve

**Extension**:
- Pairs trading via OLS regression
- Residual mean reversion on spread

**Tech Used**: `pandas`, `matplotlib`, `yfinance`, `statsmodels`

---

### 3️⃣ Momentum / Trend-Following Strategy

**Goal**: Trade based on trend continuation using price momentum and moving averages.

**Methods Used**:
- Rate of Change (past return > 0)
- Simple Moving Average (SMA) crossover

**Features**:
- Position signal generation
- Lagged execution logic
- Equity curve & metrics vs buy-and-hold

**Tech Used**: `pandas`, `matplotlib`, `yfinance`

---

## 📊 Metrics Computed

- ✅ CAGR (Compounded Annual Growth Rate)
- ✅ Sharpe Ratio (risk-adjusted performance)
- ✅ Maximum Drawdown
- ✅ Volatility
- ✅ Total Return

---

## 🧠 Concepts Covered

- Momentum vs Mean Reversion logic
- Rolling statistics
- Signal vectorization
- Regression-based spread trading
- Backtesting with lagged returns

---

---

## 🚧 In Progress

- Project 4: Pairs Trading (Regression & Cointegration)
- Project 5: Volatility Breakout
- Project 6: Sentiment Strategy with NLP

---

## 📬 Contact

Created by **Ceiron Dushyanthan**  
Feel free to reach out on GitHub for collaboration or questions.
