# PrimeTrade.ai - Data Science Assignment

## Overview

In this project, I analyzed the relationship between Bitcoin market sentiment (Fear & Greed Index) and trading performance using the Hyperliquid historical trading dataset.

The goal was to understand whether market sentiment has any impact on trader profitability and identify useful patterns from the data.

---

## Dataset

The analysis uses two datasets:

- Historical trader data from Hyperliquid
- Bitcoin Fear & Greed Index

The datasets were merged using the trade date so that each trade could be associated with the market sentiment on that day.

---

## Steps Performed

- Loaded both datasets using Pandas
- Checked for missing values
- Converted date columns into a common format
- Merged the datasets on the Date column
- Removed rows where sentiment data was unavailable
- Performed exploratory data analysis
- Created visualizations to compare trading performance across different market sentiments

---

## Analysis Included

- Average Closed PnL by market sentiment
- Win rate across sentiment categories
- Buy vs Sell performance
- Top profitable coins
- Trading volume by sentiment
- Correlation between numerical features

---

## Results

Some observations from the analysis:

- Trades executed during **Extreme Greed** had the highest average Closed PnL.
- **Fear** also showed relatively strong profitability.
- **Neutral** and **Extreme Fear** periods had lower average returns.
- Most trades had a Closed PnL close to zero, while a smaller number of profitable trades contributed significantly to the total profit.

---

## Project Structure

```
Primetrade_Assignment/
│
├── data/
│   ├── historical_data.csv
│   └── fear_greed_index.csv
│
├── images/
│   ├── profit_by_sentiment.png
│   ├── win_rate_by_sentiment.png
│   ├── buy_vs_sell.png
│   ├── top_profitable_coins.png
│   ├── trading_volume_by_sentiment.png
│   └── correlation_heatmap.png
│
├── analysis.ipynb
└── README.md
```

---

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## How to Run

1. Install the required Python libraries.
2. Open `analysis.ipynb`.
3. Run the notebook from top to bottom.

---

## Author
Lodi Tharuni