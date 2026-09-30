# 🍕 Pizza Sales Analysis

An end-to-end data analytics project analyzing pizza sales data using **PostgreSQL and Microsoft Excel**.

The project covers data analysis through SQL and presents the results in an interactive Excel dashboard with KPIs, charts, filters, and sales insights.

## 📊 Dashboard Preview

![Pizza Sales Dashboard](images/pizza-sales-dashboard.png)

## 🎯 Project Objective

The objective of this project is to analyze pizza sales data and identify:

* Overall revenue and order performance
* Sales trends by day and hour
* Sales contribution by pizza category and size
* Best and worst-selling pizzas
* Average order and pizza metrics

The analysis was performed using PostgreSQL, and the results were used to build a dynamic Excel dashboard.

## 🛠️ Tools & Technologies

* **PostgreSQL** — Data analysis and SQL queries
* **Microsoft Excel** — Dashboard development and visualization
* **SQL** — Aggregation, grouping, filtering, date/time analysis and ranking
* **Excel Pivot Tables & Slicers** — Interactive dashboard filtering

## 📁 Project Structure

```text
Pizza-Sales-Analysis/
│
├── README.md
│
├── data/
│   └── pizza_sales.csv
│
├── sql/
│   └── pizza_sales_analysis.sql
│
├── dashboard/
│   └── Pizza_Sales_Dashboard.xlsx
│
└── images/
    └── pizza-sales-dashboard.png
```

## 📌 Business Questions Analyzed

1. What is the total revenue?
2. What is the average order value?
3. How many pizzas were sold?
4. How many total orders were placed?
5. What is the average number of pizzas per order?
6. What is the daily trend of total orders?
7. What is the hourly trend of total orders?
8. What percentage of sales comes from each pizza category?
9. What percentage of sales comes from each pizza size?
10. How many pizzas were sold by category?
11. What are the top 5 best-selling pizzas?
12. What are the bottom 5 worst-selling pizzas?

## 📈 Dashboard Features

The Excel dashboard includes:

* Total Revenue KPI
* Average Order Value KPI
* Total Pizzas Sold KPI
* Total Orders KPI
* Average Pizzas per Order KPI
* Daily order trend
* Hourly order trend
* Sales by pizza category
* Sales by pizza size
* Total pizzas sold by category
* Top-selling pizzas
* Bottom-selling pizzas
* Date/month filters
* Interactive dashboard filtering

## 🔍 Key Analysis

The analysis uses SQL aggregation to calculate important business metrics.

Examples include:

```sql
SUM(total_price)
```

for total revenue,

```sql
COUNT(DISTINCT order_id)
```

for total orders, and

```sql
SUM(quantity)
```

for total pizzas sold.

Daily and hourly trends were analyzed using PostgreSQL date/time functions.

Pizza categories and sizes were compared using total sales and percentage contribution.

## 💡 Key Insights

The dashboard can be used to identify:

* The days with the highest order volume
* The busiest ordering hours
* Which pizza categories contribute the most revenue
* Which pizza sizes generate the highest sales
* The best-performing pizzas by quantity sold
* Pizzas with relatively low sales volume

## 🚀 Workflow

```text
Raw Pizza Sales Data
        ↓
Data Import
        ↓
PostgreSQL
        ↓
SQL Analysis
        ↓
Business Metrics
        ↓
Excel
        ↓
Interactive Dashboard
```

## 📚 SQL Concepts Used

* `SELECT`
* `SUM()`
* `COUNT()`
* `COUNT(DISTINCT)`
* `GROUP BY`
* `ORDER BY`
* `LIMIT`
* `ROUND()`
* Subqueries
* Window functions
* `EXTRACT()`
* `TO_CHAR()`
* Date/time analysis

## 📂 Dataset

The dataset contains pizza order information including:

* Order ID
* Pizza ID
* Pizza Name
* Pizza Category
* Pizza Size
* Quantity
* Order Date
* Order Time
* Unit Price
* Total Price
* Ingredients

## 👨‍💻 Author

**Himanshu Chaurasiya**


B.Tech CSE (Data Science)

---

⭐ If you found this project useful, feel free to explore the SQL queries and dashboard.
