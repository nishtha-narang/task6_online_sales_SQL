# task6_online_sales_SQL
This task focuses on analysing monthly revenue and order volume from sales data.

# Dataset #
The dataset contains an orders table with the following columns:
+------------+-----------+----------------------------------+
| Column Name| Data Type | Description                      |
+------------+-----------+----------------------------------+
| order_id   | VARCHAR   | Unique identifier for each order |
| order_date | DATE      | Date when the order was placed   |
| amount     | INT       | Total amount of the order        |
| product_id | VARCHAR   | Identifier of the product ordered|
+------------+-----------+----------------------------------+

# Objectives #
- Extract the month name from order dates using DATENAME (MONTH, ORDER_DATE)
- Group data by name of the month to maintain accuracy 
- Calculate total monthly revenue with SUM(amount)
- Count unique orders per month using COUNT(DISTINCT order_id)
- Sort results by revenue using ORDER BY
- Limit analysis to specific amount ranges with HAVING clause filters

# Key SQL Concepts Used #
- Date extraction and formatting
- Aggregation functions (SUM, COUNT(DISTINCT))
- Grouping and filtering data
- Sorting results for clear reporting
