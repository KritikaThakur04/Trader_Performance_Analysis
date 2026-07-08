# Trader Performance vs Market Sentiment Analysis

Objective--
The objective of this project is to analyze how Bitcoin market sentiment (Fear/Greed Index) influences trader behavior and trading performance on the Hyperliquid platform.

Dataset--
1. Bitcoin Market Sentiment
- Date
- Classification (Fear, Greed, etc.)

2. Historical Trader Data
- Account
- Execution Price
- Size USD
- Side
- Closed PnL
- Fee
- Timestamp
- Direction

Tools Used--
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

Project Workflow--
1. Loaded both datasets.
2. Checked missing values and duplicates.
3. Converted timestamps to datetime.
4. Merged datasets using date.
5. Created trading metrics.
6. Performed exploratory data analysis.
7. Compared trader performance across different market sentiments.
8. Built a simple machine learning model.

Features Created--
- Daily PnL
- Win Rate
- Average Trade Size
- Trade Frequency
- Long/Short Ratio
- Leverage Proxy (Trade Size)

Machine Learning--

Model Used:
- Linear Regression

Target:
- Closed PnL

Evaluation Metrics:
- R² Score
- Mean Squared Error

Results--
The analysis shows that trader performance changes according to market sentiment. Traders generally become more active during Greed periods, while Fear periods encourage more conservative trading behavior.

---

## Author

Kritika Thakur
