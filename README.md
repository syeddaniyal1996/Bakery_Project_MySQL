# Bakery_Project_MySQL
In today’s data-driven world, even small businesses like bakeries rely on insights from their data to make smarter decisions. A bakery doesn’t just sell cakes and pastries, it manages products, customers, orders, employees, and sales trends. 

# Data Modelling Overview
<img width="1122" height="833" alt="ERD" src="https://github.com/user-attachments/assets/d351b21d-52f1-42d6-909c-571d562aa901" />

# Insights from the Bakery MySQL Project

After running all the SQL queries on the bakery dataset, here are the key insights we can highlight:

# 1. Product Sales Insights (ordered_items)

Certain products contribute a much higher percentage of sales compared to others — this helps the bakery decide which items are best-sellers vs. which might need promotions or discounts.

By calculating percentages, we see how each product performs against the overall sales.

Ranking products by total sales makes it easier to prioritize inventory and marketing efforts.

# 2. Customer Insights (customers & customer_orders)

Some customers place frequent small orders, while others place fewer but high-value orders. Both types are important for business strategy.

Identifying top-spending customers helps in loyalty programs, discounts, or targeted offers.

Knowing the maximum order value per customer gives insights into their purchasing power.

Tracking top 2 orders per customer shows whether customers consistently buy in large amounts or if big purchases are occasional.

# 3. Employee Insights (employees)

Ranking salaries within departments allows management to see if there are pay gaps or fairness issues.

Comparing employee salaries using LAG() highlights differences in pay structure and helps in salary benchmarking.

Departments with top earners can be analyzed for performance vs. compensation alignment.

# Software and Tools Used

For this project, the following tools and technologies were used:

-> MySQL Database

Core database system used to store and query bakery data.

Queries written in SQL (Structured Query Language) for data retrieval and analysis.

MySQL Workbench (or any SQL client like DBeaver / HeidiSQL)

For writing queries, running them, and visualizing results.

Dataset (Bakery Database)

# Tables: ordered_items, customers, customer_orders, and employees.

Simulated real-world bakery transactions, customer details, and employee records.
