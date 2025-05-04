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
    
 ## **Technologies Used**
 - **Excel**
