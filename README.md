***

# Pizza Sales Analytics Dashboard (SQL)

## Short Description / Purpose

The Pizza Sales Analytics Dashboard is a SQL-driven business intelligence project focused on uncovering insights from point-of-sale data for a hypothetical pizza restaurant. This analytical solution allows managers, analysts, and data enthusiasts to dig deep into order behaviors, revenue generation, product preferences, and category performance to support smarter operational and marketing decisions.

## Project Objective

The core objective is to deliver data-driven answers to crucial business questions around order volume, sales revenue, product trends, and time-based purchasing patterns. By leveraging SQL for data extraction and aggregation, the project empowers stakeholders to optimize menu composition, forecast demand, tailor promotions, and boost overall profitability based on robust sales analytics.

## Dataset Used

The dataset comprises several interlinked tables representing real-life sales transactions, including:
- ([Orders]()): ~21,350 orders with corresponding timestamps and order details.
- ([Pizzas]()): Menu items with price, size, and pizza type associations.
- ([PizzaTypes]()): Descriptors for each menu item, including name and category.
- ([OrderDetails]()): Quantity breakdown and assignments to specific pizzas.
These tables simulate a normalized sales database and enable granular analysis via SQL joins and aggregations.

## Key Questions (KPIs)

-Retrieve the total number of orders placed.
-Calculate the total revenue generated from pizza sales.
-Identify the highest-priced pizza.
-Identify the most common pizza size ordered.
-List the top 5 most ordered pizza types along with their quantities.
-Join the necessary tables to find the total quantity of each pizza category ordered.
-Determine the distribution of orders by hour of the day.
-Join relevant tables to find the category-wise distribution of pizzas.
-Group the orders by date and calculate the average number of pizzas ordered per day.
-Determine the top 3 most ordered pizza types based on revenue.
-Calculate the percentage contribution of each pizza type to total revenue.
-Analyze the cumulative revenue generated over time.
-Determine the top 3 most ordered pizza types based on revenue for each pizza category.

## Process

- Data ingestion and setup: Structured the raw tables and relationships in a relational database.
- SQL querying: Crafted multiple aggregation, grouping, and filtering queries for KPI extraction (using techniques like JOIN, GROUP BY, SUM, and analytic functions).
- Analysis: Identified trends in order volume, product performance, and revenue contribution.
- Visualization Outputs: Summarized results for clear, actionable reporting (e.g., top sellers, sales by date, and hourly trends).
- Validation: Double-checked calculations with SQL result grids to ensure accuracy and meaningful insights.

### Dashboard Interaction (for BI tools usage)

While primarily a SQL-based project, outputs are well-suited for visualization via BI tools (e.g., Power BI, Tableau), with results supporting dynamic filtering by date, product category, pizza size, and type. Standard export tables allow for easy drill-downs and time-series analyses.

## Summary KPIs

- Total Orders: 21,350
- Total Sales Revenue: ₹817,860.05
- Most Expensive Pizza: The Greek Pizza (₹35.95)
- Most Popular Size: Large (L) with 18,526 orders

## Key Sales & Business Insights

- The top 5 most ordered pizzas include Classic Deluxe, Barbecue Chicken, Hawaiian, Pepperoni, and Thai Chicken.
- The Classic category drives the largest number of orders, while Chicken and Supreme pizzas lead in high-value revenue slices.
- Peak order times are from noon to early evening, suggesting optimal hours for staffing and promotions.
- The Thai Chicken Pizza, Barbecue Chicken Pizza, and California Chicken Pizza are the highest revenue generators.
- Classic pizzas contribute 26.91% of total revenue, followed closely by Supreme, Chicken, and Veggie categories.
- Cumulative revenue visualization uncovers seasonality and steady order streams across the reporting period.

## Business Impact & Insights

- Data pinpoints bestsellers to prioritize for marketing, combo offers, and inventory planning.
- Pizza size and timing analysis improves kitchen operations, staffing, and supply chain support.
- Revenue breakdown by pizza type/category suggests pricing optimization and new product focus areas for menu development.
- Hourly pattern and cumulative revenue help with forecasting and peak-load management.

## Final Conclusion

The SQL Pizza Sales Analytics project delivers detailed, actionable insights into ordering habits, menu performance, and time-based purchasing, directly informing management decisions on product offerings, inventory, and promotion strategies. Using SQL as an analytics backbone, the dashboard enables repeatable, scalable sales analysis for any growing restaurant business.

## Tech Stack

- MySQL / PostgreSQL (standard SQL queries)
- Relational Database Schema Design
- SQL Aggregation & Analytic Functions
- Result Table Exports for BI Visualization

***

This comprehensive description is designed for GitHub, LinkedIn, and data portfolio use, capturing both technical rigor and business context in the style requested.[1]

[1](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/99293206/90c1e5da-e886-4327-9d61-2febd08192c0/SQL-PIZZA-SALES-PROJECT.pdf)
