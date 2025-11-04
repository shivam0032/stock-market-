This update enhances the stock market analytics project with advanced statistical and visual analysis tools to better understand relationships and risk among top Indian companies.


Key Features Added
This commit introduces a Python script that uses the yfinance library to download historical stock data for major Indian companies listed on NSE. 
This script forms the foundation for future analysis and visualization of stock performance trends using pandas, matplotlib, or machine learning models.


1. 📊 Correlation Heatmap (Market Relationship Insight)
   - Calculated daily percentage returns for all 20 NSE-listed companies.
   - Generated a correlation matrix using pandas to measure inter-stock relationships.
   - Visualized the matrix as a heatmap using matplotlib/seaborn to easily identify:
       • Highly correlated stocks (moving together)
       • Negatively correlated or independent stocks (useful for diversification)

2. ⚡ Volatility Analysis
   - Computed volatility for each stock as the standard deviation of daily returns.
   - Ranked companies by volatility to identify stable (low-risk) and high-risk stocks.
   - Visualized results using a clean bar chart for quick comparison.

3. 🧠 Analytical Insights
   - Enables portfolio planners to detect diversification opportunities.
   - Helps identify which sectors or companies are more sensitive to market fluctuations.

 Technical Notes
- Used pandas for return calculations and seaborn for heatmap visualization.
- Ensured compatibility with previously downloaded data (`all_stock_data` dictionary).
- Modular structure allows easy extension into risk-return (Sharpe ratio) or ML-based forecasting models.

These enhancements elevate the project from simple data visualization to actionable market intelligence, laying groundwork for predictive analytics and portfolio optimization in upcoming versions.
