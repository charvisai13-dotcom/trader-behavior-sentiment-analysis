# Trader Behavior vs Market Sentiment Analysis

## 📌 Objective
This project analyzes how trader performance and behavior change under different
market sentiment regimes (Fear vs Greed).

We investigate whether sentiment impacts:
- Profitability (PnL)
- Trading frequency
- Win rate
- Position bias (Long vs Short)
- Risk-taking behavior

---

## 📊 Methodology

### 1. Data Preparation
- Combined daily sentiment classification with trader-level execution data.
- Aggregated trades into daily behavioral metrics:
  - Daily PnL per trader
  - Trade count per day
  - Win rate
  - Average trade size
  - Long/Short ratio

### 2. Sentiment Regime Mapping
Each trading day labeled as:
- **Fear**
- **Greed**

Merged datasets on date to analyze behavioral shifts.

---

## 🔎 Analysis Performed

We compared trader behavior across sentiment regimes using:
- Distribution plots of PnL, trade activity, and positioning
- Aggregated summary statistics
- Correlation analysis of behavioral metrics

---

## 📈 Key Insights

1. **Trading Activity Drops During Fear**
   - Traders reduce participation and become more selective.

2. **Risk-Taking Increases During Greed**
   - Higher trade frequency and directional conviction observed.

3. **PnL Distribution Becomes More Volatile in Fear Regimes**
   - Indicates defensive or inconsistent strategies under stress.

---

## ✅ Strategy Recommendations

**Rule 1 — Risk Adjustment by Sentiment**
> Reduce exposure and position size during Fear regimes to control volatility risk.

**Rule 2 — Selective Aggression During Greed**
> Allow higher participation but monitor overtrading risk signals.

Sentiment should be treated as a **risk regime indicator**, not a directional signal.

---

## ⚙️ How to Run

## ⚙️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/charvisai13-dotcom/trader-behavior-sentiment-analysis.git
```

2. Install dependencies:

```bash
pip install pandas matplotlib seaborn jupyter
```

3. Launch notebook:

```bash
jupyter notebook analysis.ipynb
```
