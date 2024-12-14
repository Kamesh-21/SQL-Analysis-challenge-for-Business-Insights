# SQL Analysis Challenge for Business Insights
## Project Overview
This project involved solving a SQL-based challenge designed by a data analytics manager to evaluate the technical problem-solving skills of aspiring data analysts. 
The dataset provided contained business data, and the goal was to extract meaningful insights to support informed decision-making.

## Role & Responsibilities
- Analyzed business data using SQL to identify patterns and trends.
- Wrote and optimized complex SQL queries to solve real-world business scenarios.
- Ensured data quality and consistency while extracting insights from raw data.

## Tools and Skills
- Tools: SQL
- Skills: Data analysis, query optimization, problem-solving , presentation skill

## Challenges Faced
- Query Optimization: Reduced execution time for large datasets through advanced SQL techniques.
- Complex Query Building: Structured multi-level SQL queries to derive actionable insights.
- Data Quality Issues: Handled incomplete and inconsistent data to ensure accurate results.

## Outcome
- Extracted meaningful insights that led to actionable business recommendations.
- Enhanced SQL query-building skills by addressing real-world business challenges.
- Gained hands-on experience in analyzing datasets to support data-driven decision-making.

## Dataset Overview
1. dim_customer: contains customer-related data
2. dim_product: contains product-related data
3. fact_gross_price: contains gross price information for each product
4. fact_manufacturing_cost: contains the cost incurred in the production of each product
5. fact_pre_invoice_deductions: contains pre-invoice deductions information for each product
6. fact_sales_monthly: contains monthly sales data for each product.

## Ad-Hoc request
1. Provide the list of markets in which customer "Atliq Exclusive" operates its business in the APAC region.

2. What is the percentage of unique product increase in 2021 vs. 2020? The final output contains these fields,
- unique_products_2020
- unique_products_2021
- percentage_chg
  
3. Provide a report with all the unique product counts for each segment and sort them in descending order of product counts. The final output contains
2 fields,
- segment
- product_count
  
4. Follow-up: Which segment had the most increase in unique products in 2021 vs 2020? The final output contains these fields,
- segment
- product_count_2020
- product_count_2021
- difference
  
5. Get the products that have the highest and lowest manufacturing costs. The final output should contain these fields,
- product_code
- product
- manufacturing_cost
 
6. Generate a report which contains the top 5 customers who received an average high pre_invoice_discount_pct for the fiscal year 2021 and in the Indian market.
 The final output contains these fields,
- customer_code
- customer
- average_discount_percentage
  
7. Get the complete report of the Gross sales amount for the customer “Atliq Exclusive” for each month. This analysis helps to get an idea of low and
high-performing months and take strategic decisions.The final report contains these columns:
- Month
- Year
- Gross sales Amount
  
8. In which quarter of 2020, got the maximum total_sold_quantity? The final output contains these fields sorted by the total_sold_quantity,
- Quarter
- total_sold_quantity
  
9. Which channel helped to bring more gross sales in the fiscal year 2021 and the percentage of contribution? The final output contains these fields,
- channel
- gross_sales_mln
- percentage
  
10. Get the Top 3 products in each division that have a high total_sold_quantity in the fiscal_year 2021? The final output contains these fields,
- division
- product_code
- product
- total_sold_quantity
- rank_order

