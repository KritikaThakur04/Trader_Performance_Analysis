1.Methodology--
The project began by loading the Bitcoin Fear & Greed dataset and the Hyperliquid trader dataset. Both datasets were inspected for missing values, duplicate records and data types. Timestamp columns were converted into datetime format, and a common date column was created to merge both datasets.
After merging, several trading metrics such as Daily PnL, Win Rate, Average Trade Size, Trade Frequency and Long/Short Ratio were calculated. Since the dataset did not contain leverage information, Average Trade Size was used as a proxy for trader exposure.
Exploratory Data Analysis was then performed using tables and visualizations to compare trader behaviour across different market sentiment conditions. Finally, a simple machine learning model was built to predict trader profitability.

2.Key Insights--
i)Trader profitability differed across market sentiment conditions, with some sentiment categories showing higher average profits.
ii)Trading activity changed with market sentiment, indicating that traders adjusted their behaviour depending on market conditions.
iii)Frequent traders generally generated higher cumulative profits, while consistent winners maintained a higher win rate than other traders.

3.Strategy Recommendations--
i)During Fear periods, traders should reduce position size and avoid unnecessary trades to minimize risk.
ii)During Greed periods, traders may increase trading activity cautiously while maintaining proper risk management.
iii)Consistently profitable traders should continue following disciplined trading strategies instead of reacting emotionally to market sentiment.
