
# 📘 Bitcoin Sentiment vs Trader Performance

## 🧠 Executive Summary
This project analyzes the correlation between Bitcoin market sentiment and trader performance using real trading data from Hyperliquid and sentiment classification from the Fear & Greed Index.

By merging and analyzing both datasets, this notebook uncovers patterns and delivers actionable insights that help traders align strategies with prevailing market emotions.

---

## 📁 Data Sources

- **Sentiment Data**: `fear_greed_index.csv`
    - Columns: `date`, `classification` (Fear, Greed, etc.)
- **Trader Data**: `historical_data_sample.csv` *(downsized for GitHub upload)*
    - Columns: `Timestamp IST`, `Coin`, `Side`, `Closed PnL`, etc.

> 📦 The full dataset (`historical_data.csv`) exceeds GitHub’s 100MB limit. 
> 📦 [Download Full Dataset (Google Drive)](https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing)



---

## 📊 Key Analyses

- ✅ Average PnL across market sentiment
- ✅ PnL breakdown by direction (Buy/Sell)
- ✅ Hourly PnL trends per sentiment
- ✅ Coin-wise PnL heatmap by sentiment
- ✅ Volatility (risk) during fear vs greed phases

---

## 🎯 Strategy Recommendations

| Sentiment        | Strategy                                  |
|------------------|--------------------------------------------|
| Extreme Fear     | Avoid new positions, reduce leverage       |
| Fear             | Use tight stop-losses, go short cautiously |
| Neutral          | Range-bound strategy, small lots           |
| Greed            | Ride trend, prefer long setups             |
| Extreme Greed    | Use trailing SL, expect reversals soon     |

---

## ✅ Conclusion

Greedy markets yield stronger long-trade profitability, while fearful markets are more volatile and risky. By aligning with sentiment, traders can improve timing, position sizing, and risk control.

---

## 📂 Files in this Repo

- `Bitcoin_Sentiment_Analysis_Final.ipynb` – Full annotated Jupyter notebook
- `fear_greed_index.csv` – Sentiment classifications
- `historical_data_sample.csv` – Trimmed trading data
- `README.md` – This file


---

> For any queries or the full dataset, feel free to reach out!
