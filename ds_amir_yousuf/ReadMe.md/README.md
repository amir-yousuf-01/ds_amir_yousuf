
# DS Project - Amir Yousuf

## Summary
This project analyzed historical trading data from Hyperliquid and the Bitcoin Market Sentiment Dataset (Fear & Greed Index) to understand how market sentiment influences trader behavior. The dataset `historical_data.csv` contained trader activities (e.g., buy/sell sides, execution prices, PNL), while `fear_greed_index.csv` provided daily sentiment scores ranging from Extreme Fear to Extreme Greed.

The analysis involved cleaning and standardizing timestamp data to align with daily sentiment values, followed by exploratory data analysis (EDA) to generate statistics and visualizations. Key steps included merging the datasets, calculating daily metrics (total volume, average PNL, risk), and assessing correlations between sentiment and trading patterns. Visualizations such as the Fear & Greed Index trend, daily trading volume, correlation heatmap, and metrics by sentiment classification were produced to support the findings.

## Conclusion
The analysis revealed several insights into the relationship between market sentiment and trader behavior:

- **Trading Volume Trends**: Higher trading volumes were observed during periods of Extreme Greed, suggesting increased market activity when sentiment is optimistic.  
- **Risk Assessment**: The standard deviation of PNL (pnl_std) tended to increase during Extreme Fear periods, indicating higher risk-taking or volatility.  
- **Trading Strategies**: A notable pattern emerged where buy ratios were higher during Extreme Fear, hinting at potential contrarian trading opportunities. This suggests that buying during fear-driven market dips could yield profits, as supported by positive average PNL in such conditions.  
- **Recommendations**: Traders may consider implementing a strategy of increasing buy positions during Extreme Fear, while monitoring risk closely. Further analysis with a larger dataset or additional features (e.g., market volatility) could refine these insights.

The project was completed on **September 09, 2025, at 05:10 PM IST**, with all outputs consolidated in `ds_report.pdf` for a summarized presentation.

## Notes
- The project analyzes how trader behavior (e.g., buy/sell ratios, profitability) correlates with market sentiment (Fear vs. Greed).  
- Timestamp data was standardized to daily values to align with sentiment data.  
- All code and data processing are reproducible via the Colab notebook.