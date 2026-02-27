# FNP-Customer-Shopping-Behavior-Analysis-Excel
End-to-end Excel project analyzing FNP (Ferns and Petals) sales and customer shopping behavior using data cleaning, pivot tables, and dashboards to derive business insights.

## Project Overview
This is an end-to-end Excel data analysis project based on sales data from FNP (Ferns and Petals), a gifting company offering products for multiple occasions such as festivals, birthdays, anniversaries, and special events.

The project focuses on understanding customer shopping behavior, sales trends, product performance, and delivery timelines using Excel.

## Business Objective
The objective of this analysis is to:
- Analyze overall sales performance
- Understand customer purchasing patterns
- Identify high-performing products and occasions
- Evaluate delivery efficiency
- Support data-driven business decisions

## Data Model & Relationships
The project follows a relational data model using three datasets loaded as separate sheets in Excel.

- **Customers → Orders**  
  One-to-many relationship using `Customer_ID`, where one customer can place multiple orders.

- **Products → Orders**  
  One-to-many relationship using `Product_ID`, where one product can appear in multiple orders.

The **Orders dataset** acts as the central fact table, while **Customers** and **Products** serve as dimension tables.  
This structure enables accurate analysis of customer behavior, product performance, sales trends, and delivery insights using pivot tables and dashboards.

## Tools & Techniques Used
- Microsoft Excel
- Relational data modeling in Excel
- Excel formulas
- Pivot Tables and Pivot Charts
- Interactive Excel Dashboard

## Data Preparation
- Reviewed datasets for structure and consistency
- Used Customers, Orders, and Products as separate sheets
- Created calculated columns such as:
  - Revenue
  - Order Month Name
  - Order Day
  - Order Hour
  - Delivery Time Difference
- Ensured correct relationships using Customer_ID and Product_ID

## Analysis Performed
The following analyses were performed using Excel pivot tables and charts:

- Total revenue analysis
- Average order and delivery time analysis
- Monthly sales performance
- Top products by revenue
- Customer spending analysis
- Sales performance of top 5 products
- Top 10 cities by number of orders
- Order quantity vs delivery time analysis
- Revenue comparison across different occasions
- Product popularity by occasion

## Conclusion
This end-to-end Excel project demonstrates how structured data modeling, pivot table analysis, and dashboards can be used to analyze customer shopping behavior and sales performance.

The insights derived from this analysis can help FNP improve product strategy, optimize delivery timelines, and make data-driven marketing and business decisions.

