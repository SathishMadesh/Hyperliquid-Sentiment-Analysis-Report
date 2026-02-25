# Hyperliquid Trader Behavior vs Market Sentiment

## Overview

This project analyzes how market sentiment (Fear vs Greed) affects trader behavior and performance on Hyperliquid.

We combine:

* Bitcoin Fear & Greed Index
* Hyperliquid historical trades

Goal:
Understand how sentiment influences:

* Profitability
* Trade behavior
* Risk-taking

---

## Datasets

### 1. Market Sentiment

Contains:

* Date
* Fear/Greed classification
* Sentiment value

### 2. Trader Data

Contains:

* Account
* Trade size
* Side (Buy/Sell)
* PnL
* Timestamp

---

## Metrics Created

We computed:

* Daily PnL per trader
* Win rate
* Average trade size
* Trades per day
* Long/Short ratio

---

## Methodology

1. Clean datasets
2. Convert timestamps
3. Merge by date
4. Compute metrics
5. Analyze sentiment impact
6. Generate charts

---

## How to Run

Install dependencies:

```
pip install -r requirements.txt
```

Run notebook:

```
jupyter notebook notebooks/analysis.ipynb
```

---

## Results

### PnL vs Sentiment

Shows profitability differences between Fear and Greed.

### Trades vs Sentiment

Shows trader activity levels.

### Size vs Sentiment

Shows risk-taking behavior.

### Long/Short Ratio

Shows directional bias.

---

## Insights

1. Traders take larger positions during Greed.
2. Trading activity increases during Greed.
3. Losses increase during Fear.

---

## Strategy Recommendations

### Strategy 1 — Risk Control

During Fear:

* Reduce leverage
* Reduce position size

### Strategy 2 — Activity Strategy

During Greed:

* Increase trading activity
* Use momentum trades

---

## Files

```
data/        → datasets
notebooks/   → analysis
outputs/     → charts
```

---

## Author

Sathish M
