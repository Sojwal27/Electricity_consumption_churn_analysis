# Executive Summary: Electricity Consumption & Churn Analysis

## Project Overview

This analysis examines electricity consumption patterns and customer churn trends in India from 2000-2001 to 2007-2008. The study utilizes historical data from electricity sales to ultimate consumers, categorized by sector and state, to identify consumption trends, growth patterns, and potential churn indicators.

## Key Findings

### Consumption Trends
- **Total Electricity Consumption**: Increased significantly from 209,217 units in 2000-01 to 501,977 units in 2007-08, representing a compound annual growth rate (CAGR) of approximately 12.5%.
- **Sector Distribution**: Agriculture accounts for the largest share (approximately 20-25% of total consumption), followed by Industrial High Voltage and Domestic sectors.
- **Growth Patterns**: Most sectors showed positive growth over the period, with Industrial High Voltage exhibiting the strongest growth trajectory.

### Churn Analysis
- **Churn Definition**: Churn is identified as periods of consumption decline greater than 5% year-over-year within specific sectors.
- **High-Risk Sectors**: Agriculture experienced notable churn in 2001-02 (-3.6%), indicating potential vulnerability in this sector.
- **Volatility Insights**: The analysis identifies years with high consumption volatility across sectors, highlighting periods of market instability.

### Geographic Insights
- **State-Level Consumption**: Maharashtra, Uttar Pradesh, and Andhra Pradesh emerge as the top consuming states, representing significant concentration risk.
- **Regional Variations**: Consumption patterns vary widely across states, with some regions showing stronger growth than others.

## Business Implications

### Strategic Recommendations
1. **Sector Focus**: Prioritize retention strategies for agriculture sector due to its large consumption share and observed churn events.
2. **Growth Opportunities**: Invest in Industrial High Voltage sector, which demonstrates consistent growth and high consumption volumes.
3. **Risk Mitigation**: Develop contingency plans for high-volatility periods to maintain stable revenue streams.

### Operational Insights
- **Data-Driven Decision Making**: The processed datasets enable real-time monitoring of consumption patterns and early churn detection.
- **PowerBI Integration**: Interactive dashboards provide stakeholders with visual tools for trend analysis and strategic planning.

## Methodology

The analysis employed:
- Data cleaning and preprocessing of raw Excel datasets
- Time-series analysis of consumption patterns
- Year-over-year growth calculations
- Churn identification based on significant consumption declines
- Geographic analysis across Indian states

## Data Sources

- Primary dataset: Electricity sales to ultimate consumers (2000-2008)
- Processed datasets optimized for analysis and visualization
- State-wise consumption data for geographic insights

## Conclusion

This comprehensive analysis reveals a growing electricity market with sector-specific opportunities and risks. The identification of churn patterns and growth sectors provides actionable insights for energy sector stakeholders. Continued monitoring and analysis of these trends will be crucial for sustainable energy planning and customer retention strategies.

## Next Steps

1. Implement real-time monitoring systems for early churn detection
2. Develop targeted retention programs for high-risk sectors
3. Expand analysis to include more recent data for trend validation
4. Integrate predictive modeling for future consumption forecasting

---

*Analysis conducted using Python (pandas, numpy, matplotlib, seaborn) and PowerBI for visualization.*