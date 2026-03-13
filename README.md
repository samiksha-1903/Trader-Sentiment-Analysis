# Trader Sentiment Analysis

# Project Overview
This project analyzes how market sentiment from the Bitcoin Fear & Greed Index influences trader behavior and profitability using historical trading data. By combining sentiment data with trading records, the goal is to identify patterns between market conditions and trading outcomes.

# Methodology
1. Loaded the Fear & Greed Index dataset and historical trading dataset using Python (Pandas).
2. Converted timestamps to datetime format and extracted date columns.
3. Merged the sentiment dataset with the trading dataset using the date column.
4. Cleaned the data by converting Closed PnL to numeric values and removing missing sentiment entries.
5. Created additional features such as win/loss classification.
6. Performed exploratory analysis and visualizations to understand trading performance under different sentiment conditions.

# Key Analysis & Output
- Calculated summary statistics of trading profit (Closed PnL).
- Analyzed sentiment distribution across trades.
- Compared average trader profit under different sentiment conditions.
- Examined how average trade size changes with market sentiment.
- Visualized results using:
  - Profit distribution by market sentiment (Boxplot)
  - Average trade size by sentiment (Bar Chart)
  - Winner vs Loser profit comparison

# Key Insights
1. Trader profits vary significantly across market sentiment categories, with larger profit and loss ranges during Fear and Greed market conditions.
2. Average trade sizes tend to increase during Fear and Greed periods, indicating higher risk-taking behavior.
3. Extreme sentiment conditions show higher volatility in trading outcomes.
4. Winning trades produce significantly higher profits (~283) compared to average losses (~-35), suggesting asymmetric risk-reward strategies.

# Strategy Recommendations
Strategy 1:Reduce trade size during Extreme Fear periods to limit potential downside risk.
Strategy 2:During Greed periods, traders may increase participation but should apply risk management strategies such as stop-loss limits.

# Tools Used
Python, Pandas, NumPy, Matplotlib, Seaborn

# How to Run
1. Clone or download the repository.
2. Open the notebook 'Trader_Sentiment_Analysis.ipynb'.
3. Run all cells to reproduce the analysis and visualizations.
