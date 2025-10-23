🧠 Junior Data Scientist – Trader Behavior Insights
📊 Project Overview

An analytical project exploring the correlation between individual trader performance and the Bitcoin Market Sentiment (Fear & Greed Index) to uncover behavioral trading patterns and develop data-driven strategies for systematic Web3 trading.

🎯 Objective

To analyze the relationship between trader performance metrics (PnL, Volume) and market sentiment to determine whether sentiment data can serve as a primary signal for creating smarter, automated trading strategies.

💡 Key Insights
1. Contrarian Strategy Identified

A clear and consistent Contrarian Trading Strategy emerged from the analysis.

Peak Profitability During Panic:
The trader achieves the highest profit (alpha) during periods of “Extreme Fear”, proving that buying into panic yields the most favorable results.

Losses During Euphoria:
The trader’s performance declines and often turns negative during phases of “Greed”, indicating that overconfidence leads to poor outcomes.

Actionable Outcome:
These findings form a foundation for automated trading algorithms that allocate capital and manage risk dynamically based on sentiment classification.

🧩 Project Files & Tools
📁 Input Datasets

historical_data.csv – Raw trade-level performance data from Hyperliquid.

fear_greed_index.csv – Daily Bitcoin Market Sentiment data (Fear & Greed Index).

💻 Analysis Code

Bitcoin_analysis.ipynb – Main Python notebook containing data cleaning, merging, feature engineering, and visualization logic.

🧾 Reports & Deliverables

trader_behavior_insights_report.md – Structured report summarizing findings, visual insights, and strategic recommendations.

Image Outputs – Visuals showing:

PnL vs. Sentiment

Volume vs. Sentiment

PnL Over Time

⚙️ Methodology

Data Preparation:
Cleaned and standardized both datasets for consistent date alignment.

Data Merging:
Combined trader performance with market sentiment to create a unified analysis dataset.

Exploratory Analysis:

Correlation between PnL and sentiment scores

Volume fluctuations vs. emotional market states

Time-series analysis of profitability patterns

Insight Generation:
Derived actionable behavioral and strategic insights for sentiment-based trading optimization.

📈 Conclusion

The study demonstrates that sentiment-driven contrarian trading offers significant alpha generation potential.
The trader’s best performance occurs in market fear, highlighting the opportunity for emotion-aware algorithmic trading systems.

🧠 How to Replicate

Clone Repository:

git clone <repository-link>
cd trader-behavior-insights


Run Analysis:
Open the Jupyter Notebook:

Bitcoin_analysis.ipynb


Execute the cells sequentially to reproduce the cleaned data, merged datasets, and visualizations.

Review Results:
Open the file:

trader_behavior_insights_report.md


for final findings, visuals, and recommendations.

🛠️ Tools & Technologies

Python: Pandas, NumPy, Matplotlib, Seaborn

Environment: Jupyter Notebook

Data Sources: Hyperliquid Trader Data, Fear & Greed Index
