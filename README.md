# lacevedo Superstore1
## Project Overview

This project aims to provide insites on specific sales questions. Through analizing the companies data, we are able to gain insite on the companies performance.

### Data Source

 for thid project I used SQL to query the Superstore data

 ### Tools

 SQL

 ### Eploratory Sales Analysis

 Overall sales Analysis, answering sales questions

 -List prices
 -What is the average price of an item sold
 -What is the average price of the most expensive item
 - What is the price of the least expensive item
 - What is the sum of all items sold
 - -What is the average price of an item sold

 ### Data Analysis
 ```sql
SELECT *
FROM superstore
ORDER BY price desc;

```sql

Select Max(price)
From superstore;

```sql

Select Min(price)
From superstore;

```sql

Select SUM(price)
From superstore;

```sql

Select AVG(price)
From superstore
Where item= “Kitchen Supplies”

