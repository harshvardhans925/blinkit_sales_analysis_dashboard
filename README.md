# blinkit_sales_analysis_dashboard

# Dahsboard link: https://app.powerbi.com/links/x2yywpk-Zb?ctid=4665b27a-3ddb-4591-bc0a-775b49a891bd&pbi_source=linkShare



# Objective
Analyze and enhance sales performance for Blinkit using a comprehensive Power BI dashboard.



# Key Insights
Sales Trends: Identify monthly and yearly sales patterns.
Product Analysis: Determine best-selling and underperforming products.
Customer Insights: Segment customers based on purchasing behavior.
Regional Performance: Analyze sales distribution across different regions.
Profit Analysis: Evaluate profit margins by product and region.


# Key Journey
Data Import and Cleaning: Import sales data from various sources and clean it using Power Query Editor.
Data Modeling: Establish relationships between tables and create a robust data model.
DAX Formulas: Use DAX to create calculated columns and measures for in-depth analysis.
Dashboard Design: Design an interactive dashboard with charts, maps, and slicers.
Sales Forecasting: Implement forecasting techniques to predict future sales.
Publishing and Sharing: Publish the dashboard to Power BI Service and share insights with stakeholders.

# DAX Formulas for Calculated Columns
**Sales Amount**
Formula: Sales Amount = Sales[Quantity] * Sales[Unit Price]
Explanation: This formula calculates the total sales amount for each transaction by multiplying the quantity sold by the unit price.


**Profit**
Formula: Profit = Sales[Sales Amount] - Sales[Cost]
Explanation: This formula calculates the profit for each transaction by subtracting the cost from the sales amount.


**Year**
Formula: Year = YEAR(Sales[Order Date])
Explanation: This formula extracts the year from the order date to create a new column for year-based analysis.


**Month**
Formula: Month = FORMAT(Sales[Order Date], "MMMM")
Explanation: This formula extracts the month from the order date and formats it as the full month name.

**Customer Segment**
Formula: Customer Segment = IF(Sales[Customer Type] = "Corporate", "B2B", "B2C")
Explanation: This formula categorizes customers into segments based on the customer type, labeling them as B2B (Business to Business) or B2C (Business to Consumer).


**Brief Explanation**
Sales Amount and Profit are fundamental calculations to understand revenue and profitability.
Year and Month columns are essential for time-based analysis, allowing for trend identification over different periods.
Customer Segment helps in segmenting the customer base for targeted marketing and analysis.
These calculated columns are crucial for breaking down and analyzing the data in meaningful ways, enabling more detailed and actionable insights.


# Conclusion to Improve Sales
Focus on High-Performing Products: Invest more in marketing and inventory for top-selling products.
Targeted Marketing Campaigns: Use customer segmentation data to create personalized marketing strategies.
Optimize Inventory Management: Adjust inventory levels based on sales trends and forecasts.
Expand in High-Growth Regions: Allocate resources to regions with strong sales growth.
Continuous Monitoring: Regularly monitor sales performance and adjust strategies as needed.
