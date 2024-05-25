Overview:
The AdventureWorks Sales Dashboard is a comprehensive Power BI project designed to visualize and analyze sales data from the AdventureWorks database. This dashboard provides a wide range of insights into the sales performance, customer retension, Market basket analysis and product popularity, helping businesses make informed, data-driven decisions.

Key Features:
Yearly Sales Trend Analysis: Analysed the total sales trend over the years and identify any significant growth or decline in sales.
Product Performance: Identified the top 5 products based on total sales and analyze their monthly sales trend for the last year.
Sales by Region: Compared total sales by geographical regions and highlight the best and worst performing regions.
Profitability Analysis: Calculated the profitability per product category and identify the most profitable category.
Market Basket Analysis: Performed a market basket analysis to find out which products are commonly purchased together.
Sales Channel Efficiency: Compared the efficiency of different sales channels (online vs. retail).
Customer Retention Analysis: Analysed the data to find out the retention rate of customers and factors affecting their loyalty.
Product Category Performance Comparison: Developed a measure that calculates the percentage change in sales for each product category from the previous month. Used variables to simplify the DAX expression and enhance performance.
Dynamic Top N Analysis: Implemented a dynamic measure that allows users to select the top N products based on sales. Incorporated a slicer in your report for users to choose the value of N dynamically.
Profit Margin Analysis by Region: Wrote a DAX measure to calculate the profit margin for each region. Included a dynamic filter to allow users to select specific regions or all regions, and visualize this data on a map.
Year-over-Year Growth Percentage: Created a DAX measure that calculates the Year-over-Year growth percentage for total sales. Used a date slicer to let users dynamically select the year and visualize the growth trend.
Dynamic Ranking with Slicers: Constructed a DAX measure to dynamically rank customers or products based on sales. This allows users to adjust the ranking criteria through slicers, switching between sales, quantity, or profitability.
Dynamic Measure Based on Date Ranges: Created a measure that computes total sales within a user-defined date range. Utilized a DAX measure that adjusts based on the start and end dates provided by the user through a date range slicer.
Time Intelligence Analysis: Did calculation on Year-to-Date (YTD), Quarter-to-Date (QTD), and Month-to-Date (MTD) sales and compare them with the previous periods.
