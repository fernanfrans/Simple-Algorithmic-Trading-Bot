# 📈 Simple Moving Average (SMA) Crossover Strategy
### Algorithmic Trading Strategy Implementation in Python

---

## 📌 Overview
This project implements a **Simple Moving Average (SMA) Crossover Strategy** for algorithmic trading. The strategy uses two SMAs—one short-term and one long-term—to identify potential buy and sell signals.

---

## ⚙️ Features
✔ Uses two different SMAs to generate trading signals  
✔ Automatically detects crossovers between the fast and slow SMAs  
✔ Can be used for backtesting historical stock price data  
✔ Implemented in **Python** using **pandas, NumPy, and Matplotlib**  
✔ Optimizable SMA periods for different trading strategies  

---

## 📊 Strategy Explanation
The SMA Crossover Strategy works as follows:

1. **Short SMA (Fast)**: A moving average calculated over a **shorter** period (e.g., 10 days).
2. **Long SMA (Slow)**: A moving average calculated over a **longer** period (e.g., 50 days).
3. **Buy Signal**: When the **fast SMA crosses above** the slow SMA (Golden Cross).
4. **Sell Signal**: When the **fast SMA crosses below** the slow SMA (Death Cross).

---
