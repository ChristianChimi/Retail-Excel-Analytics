## **Retail-Excel-Analytics**
This project focuses on business intelligence and retail analytics using Microsoft Excel, combining tabular data processing, pivot analysis, and data visualization.

## **Pre-Processing**
  - Create Table
  - New columns:
      - Sales =[@[Units Sold]]*[@[Unit Price]]
      - Cost =[@[Units Sold]]*[@[Unit Cost]]
      - Profit =[@Sales]-[@Cost]
      - Extract Month from date =MONTH([@[Order Date]])

## **Data Visualization**
  - Created pivots:
      - For Months, Salesman, Category, Region and product.
 - For each pivot:
    - Analyzed total Sales and Profit
    - Compared performance across segments
  - Applied Trend Lines on sales charts to highlight forecasting direction
  - Added a timeline filter by Month to allow interactive updates across all pivots
