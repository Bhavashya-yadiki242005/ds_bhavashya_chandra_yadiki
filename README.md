# ds_bhavashya_chandra_yadiki
Analysis of Bitcoin trader performance vs. market sentiment (Fear &amp; Greed Index). Includes data cleaning, EDA, visualizations, and insights on how sentiment impacts trading outcomes. Built using Python (Pandas, NumPy, Matplotlib, Seaborn) in Jupyter Notebook.

Bitcoin Market Sentiment vs Trader Performance
Project Overview

This project explores the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance using historical trade data from Hyperliquid.

By combining sentiment data with trading records, the analysis uncovers how emotions like Fear and Greed impact trading profitability, highlighting hidden patterns that can drive smarter trading strategies.

Datasets Used:

Hyperliquid Historical Trader Data:https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing

Columns: Account, Coin, Execution Price, Size, Side, Timestamp, Closed PnL, Leverage, etc.

Bitcoin Fear & Greed Index:https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing

Columns: Date, Value, Classification (Fear/Greed).

Steps in Analysis:

Data Loading & Cleaning

Loaded CSV files into Pandas.

Cleaned timestamps and numeric fields.

Handled missing values.

Data Merging

Synced trades with corresponding sentiment values by date.

Sentiment Mapping

Classified sentiment into Fear / Greed buckets.

Analysis & Insights:

Compared trader performance under Fear vs Greed conditions.

Identified traders who adapt better to each sentiment.

Visualized sentiment impact on closed PnL.

Final Summary:

Provided actionable insights on how market emotions affect profitability and strategy.

Key Insights:

Traders show different profitability patterns depending on Fear or Greed market conditions.

Some traders perform better on Fear days, while others succeed in Greed periods.

Market sentiment is a useful signal for risk management and trading strategy optimization.

Enhancement Implemented:

Trader Sentiment Responsiveness: Highlighted which traders profit more during Fear vs Greed days.

Visualizations:

Trader performance comparison under different sentiment conditions.

Charts showing how sentiment buckets influence profitability.

Conclusion:

This project demonstrates that market sentiment plays a significant role in trading performance. By mapping trades with Fear/Greed data, traders can optimize strategies, improve portfolio allocation, and better manage risks in volatile crypto markets.

Tech Stack:

Python (Pandas, NumPy, Matplotlib, Seaborn)
