## **Retail-Excel-Analytics**
This project focuses on utilizing Microsoft Excel for business intelligence and retail analytics. The analysis involves processing tabular data, performing pivot analysis, and creating visualizations to gain insights into sales performance, profitability, and key business trends.

## **Pre-Processing**
- Creating Tables: The raw data was organized into structured tables for easier analysis and to enable dynamic filtering and referencing.
- Adding New Columns:
  - Sales: Calculated using the formula [@[Units Sold]]*[@[Unit Price]], providing the total revenue from each product.
    - Cost: Calculated using [@[Units Sold]]*[@[Unit Cost]], which gives the total cost for each product sold.
    - Profit: Calculated as [@Sales]-[@Cost], representing the difference between revenue and cost.
    - Month Extraction: Created a new column to extract the month from the Order Date using the formula MONTH([@[Order Date]]).

## **Data Visualization**
-  Data was visualized and analyzed using pivot tables and charts to uncover key business insights:
- Pivot Tables: I created several pivot tables to analyze data across different dimensions:
  - Months: Analyzed trends over time to understand seasonality and sales performance.
    - Salesman: Compared the performance of different salespeople to identify top performers.
    - Category: Examined sales by product category to identify high-performing and underperforming categories.
    - Region: Assessed regional sales performance to identify geographical trends.
    - Product: Evaluated sales by individual products to identify bestsellers and slow movers.

## **Key Insights**
- Sales Trends: Analysis of sales across months revealed clear seasonal trends, helping to identify peak sales periods and better plan for demand fluctuations.
- Top Performers: Pivot analysis showed that certain salespeople outperformed others, highlighting the need for targeted training or incentivization for lower-performing team members.
- Category Performance: By examining sales by product category, high-performing categories were identified, as well as underperforming ones that may need further promotion or product adjustments.
- Regional Trends: Sales performance varied across regions, which can inform region-specific marketing strategies and resource allocation to optimize performance.
- Product Performance: Analysis of individual product sales helped identify bestsellers and slow-moving products, offering insights into inventory management and product promotion strategies.

## **Conclusions**
This project effectively demonstrates the power of Microsoft Excel for business intelligence and retail analytics. Through the use of pivot tables and charts, key business trends were uncovered, providing valuable insights into sales performance, profitability, and the effectiveness of different sales strategies. The findings offer actionable recommendations for improving sales performance, optimizing inventory, and targeting marketing efforts more effectively. Overall, Excel proved to be a robust tool for conducting in-depth retail analysis and driving data-informed business decisions.

 ## **Technologies Used**
 - **Excel**
