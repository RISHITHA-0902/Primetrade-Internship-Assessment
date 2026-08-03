# PrimeTrade.ai Internship Assessment

## Trader Performance Analysis Based on Bitcoin Market Sentiment

### Objective
The objective of this project is to analyze the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance using historical trading data from Hyperliquid.

### Dataset
1. Historical Trader Data
  https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing

3. Bitcoin Fear & Greed Index
https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing

### Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

### Methodology
- Loaded both datasets.
- Cleaned and prepared the data.
- Converted timestamps into date format.
- Merged trader data with the Fear & Greed Index.
- Performed Exploratory Data Analysis (EDA).
- Analyzed trader performance under different market sentiment conditions.
- Performed statistical testing (t-test).

### Visualizations
- Market Sentiment Distribution
- Average Closed PnL by Sentiment
- Total Closed PnL by Sentiment
- Top Traded Coins
- Top Profitable Coins
- Long vs Short Performance
- Average Trade Size by Sentiment
- Correlation Heatmap
- Profit Distribution
- Daily Closed PnL Trend
- Top 10 Profitable Traders

### Key Findings
- Fear market had the highest trading activity.
- Extreme Greed showed the highest average profit per trade.
- Fear generated the highest total profit because of higher trading volume.
- HYPE, @107 and BTC were among the most traded assets.
- Trade Size and Fee showed a strong positive correlation.
- Daily profitability became more volatile during late 2024 and early 2025.
- Statistical testing showed no significant difference between average Closed PnL during Fear and Greed periods (p > 0.05).

### Conclusion
This analysis demonstrates how Bitcoin market sentiment can be combined with trader performance data to understand trading behavior, profitability patterns, and support data-driven trading decisions.
