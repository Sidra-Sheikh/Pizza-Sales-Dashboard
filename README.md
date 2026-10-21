# Pizza-Sales-Dashboard
🍕 Pizza Sales Dashboard: Sales Performance & Trend Analysis
An interactive Power BI dashboard designed to analyze pizza sales performance, customer ordering patterns, revenue contribution, and product-level performance using SQL and data visualization.

The Pizza Sales Dashboard is a data analytics project built to evaluate pizza sales performance for the year 2015. It combines SQL-based data analysis with Power BI visualizations to transform raw sales data into meaningful business insights.

The dashboard helps users monitor key performance indicators (KPIs), identify sales trends, compare pizza categories and sizes, and evaluate the best- and worst-performing pizzas by revenue, quantity sold, and total orders. Interactive filters allow users to explore the data by pizza category, pizza size, and date range.

3. Tech Stack 🛠️
   
The project was developed using the following tools and technologies:

-🔌 Microsoft SQL Server – Imported and queried the raw pizza sales data to calculate KPIs, analyze trends, and compare product performance.

▫️ 🖥️SQL – Used aggregate functions, "GROUP BY", "ORDER BY", "WHERE", "TOP", "CAST()", and "COUNT(DISTINCT)" to perform sales analysis.

▫️ 📊 Microsoft Power BI Desktop – Used to build interactive dashboards and visual reports.

▫️🗃️ Power Query – Used for data cleaning and transformation.

▫️ 🧠DAX (Data Analysis Expressions) – Used for calculations and analytical measures in Power BI.

▫️ 📂File Format – pbix for development and  png for dashboard  preview.

4. Data Source

▫️Source: Maven Analytics
▫️Dataset: Pizza Sales Dataset
▫️File Format: CSV

The project uses raw pizza sales data containing order information, pizza names, categories, sizes, quantities, prices, and order dates.

The dataset was imported into Microsoft SQL Server, where SQL queries were executed to calculate performance metrics and analyze sales patterns. The SQL Server database was then connected to Power BI for data preparation, calculations, and interactive dashboard development.

A. Business Problem

Pizza businesses generate sales data across multiple products, categories, sizes, and ordering periods. However, raw data alone does not provide an easy way to identify sales trends, compare product performance, or monitor key business metrics.

The project addresses the need for an interactive reporting solution that helps analyze sales performance and identify high-performing and underperforming pizza products.

B. Goal of the Dashboard

The primary goals of this project are to:

▫️ Monitor key sales performance indicators.

▫️ Analyze daily and monthly order trends.

▫️ Compare sales contributions across pizza categories and sizes.

▫️ Identify the top 5 and bottom 5 pizzas by revenue, quantity sold, and total orders.

▫️ Provide interactive filters for exploring sales data.

▫️ Present business data in an accessible and visually engaging format.


C. Key Performance Indicators (KPIs)

The dashboard displays five main KPIs:

KPI| Result

▫️Total Revenue| 817.86K

▫️Average Order Value| 38.31

▫️Total Pizzas Sold| 49,574

▫️Total Orders| 21,350

▫️Average Pizzas Per Order| 2.32

These indicators provide an overview of overall sales performance, order volume, and average purchasing behavior.

D. Walkthrough of Key Visuals

1. Daily Trend for Total Orders

A bar chart compares the number of orders across the days of the week, helping identify variations in daily order activity.

2. Monthly Trend for Total Orders

A line/area chart displays monthly order patterns throughout the year, making it easier to compare busier and quieter months.

3. Percentage of Sales by Pizza Category

A doughnut chart illustrates the revenue contribution of the four pizza categories: Classic, Supreme, Chicken, and Veggie.

4. Percentage of Sales by Pizza Size

A doughnut chart compares revenue contributions across pizza sizes, including Large, Medium, Regular, X-Large, and XX-Large.

5. Total Pizzas Sold by Pizza Category

A horizontal bar chart compares the quantity sold across different pizza categories.

6. Top 5 Pizzas by Revenue

Highlights the five pizzas generating the highest revenue.

7. Bottom 5 Pizzas by Revenue

Identifies the five pizzas with the lowest revenue.

8. Top 5 Pizzas by Quantity

Shows the five pizzas with the highest total quantity sold.

9. Bottom 5 Pizzas by Quantity

Highlights the five pizzas with the lowest total quantity sold.

10. Top 5 Pizzas by Total Orders

Ranks pizzas according to the number of distinct orders containing each pizza.

11. Bottom 5 Pizzas by Total Orders

Identifies pizzas appearing in the fewest distinct orders.

12. Interactive Filters

The dashboard includes filters for pizza category, pizza size, and date range, allowing users to explore different segments of the sales data.

E. Business Impact & Insights

The dashboard provides the following observations from the displayed dataset:

▫️ Revenue: Total revenue is approximately 817.86K, with an average order value of 38.31.

▫️ Order Volume: A total of 21,350 orders and 49,574 pizzas sold are recorded.

▫️ Category Performance: Classic pizzas account for approximately 26.91% of total revenue and lead the category-wise quantity comparison, with 14,888 pizzas sold.

▫️Size Preference: Large pizzas contribute approximately 45.89% of revenue, followed by Medium pizzas at 30.49%.

▫️ Daily Ordering Pattern: Friday records the highest number of orders among the days shown in the SQL results, while Sunday records the lowest.

▫️ Monthly Ordering Pattern: July records 1,935 orders, while October records 1,646 orders in the SQL results.

▫️ Product-Level Performance: The top 5 and bottom 5 comparisons help identify products that perform strongly or may require further investigation.

These findings can support sales monitoring, product performance evaluation, menu analysis, and data-informed business decisions.

F. Project Workflow

1. Obtained the pizza sales dataset in CSV format from Maven Analytics.
2. Imported the raw dataset into Microsoft SQL Server.
3. Executed SQL queries to calculate KPIs and analyze order trends, category contributions, pizza sizes, and product rankings.
4. Connected Microsoft SQL Server to Power BI Desktop.
5. Used Power Query for data cleaning and transformation.
6. Used DAX for calculations and analytical measures.
7. Created interactive Power BI dashboards with KPIs, charts, and filters.
8. Analyzed the results to identify sales patterns and product-level insights.

6. Screenshots 

Dashboard 1: Pizzeria Performance

This dashboard presents the key sales KPIs and compares the top 5 and bottom 5 pizzas by revenue, quantity sold, and total orders.

"Pizzeria Performance Dashboard" (https://github.com/Sidra-Sheikh/Pizza-Sales-Dashboard/blob/main/Snapshot%20of%20Dashboard%201.PNG)

Dashboard 2: Pizzeria Trends

This dashboard explores daily and monthly order trends, revenue contribution by pizza category and size, and total pizzas sold by category.

"Pizzeria Trends Dashboard" (https://github.com/Sidra-Sheikh/Pizza-Sales-Dashboard/blob/main/Snapshot%20of%20Dashboard%202.PNG )



