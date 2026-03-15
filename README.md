# Pizza-Sale-Excel-Dashboard-
End to end Pizza Sales Analysis project using Oracle SQL for data querying and Excel for visualization using dashboards, including KPIs, sales trends, category analysis, and performance insights.
🍕 Pizza Sales Data Analysis Dashboard

📌 Project Overview

This project is about analyzing the given pizza sales data to gain some business insights regarding revenue generation, customer behavior, and product success. Data analysis is carried out using **Oracle SQL** and **Microsoft Excel** for visualization and creating a dashboard.

The objective of the project is to practice data analysis and SQL skills using a real-world problem and present the insights in an easy-to-understand format.

🎯 Objectives

* To analyze the total revenue generated from the sale of pizzas.
* To understand the daily and hourly order trends.
* To gain insights into the distribution of pizzas and their size.
* To identify the best-selling and worst-selling pizzas.
* To develop an interactive dashboard to gain business insights.

🛠 Tools & Technologies Used

* **Oracle SQL** - Data analysis and aggregation.
* **Microsoft Excel** - Data visualization and creating a dashboard.
* **Pivot Tables and Charts** - Data analysis.

📊 Key Performance Indicators (KPIs)

The dashboard is designed to track the following KPIs:

* **Total Revenue**
* **Average Order Value**
* **Total Pizzas Sold**
* **Total Orders**
* **Average Pizzas per Order

📈 Dashboard Insights

1. Daily Order Trends

Orders are highest on Fridays and weekends# 🍕 Pizza Sales Data Analysis Dashboard

### 2. Hourly Sales Trends

* Peak ordering times occur during **12 PM – 1 PM** and **4 PM – 8 PM**.

### 3. Sales by Pizza Category

* **Classic pizzas** contribute the highest share of sales.

### 4. Sales by Pizza Size

* **Large size pizzas** generate the most revenue.

### 5. Best Selling Pizzas

* Top pizzas contribute significantly to overall sales performance.

### 6. Worst Selling Pizzas

* Some pizzas show low demand and could require marketing or menu optimization.

---

## 🧾 SQL Analysis Performed

Key SQL operations used in this project include:

* Aggregation using `SUM`, `COUNT`, and `AVG`
* Grouping data using `GROUP BY`
* Filtering results using `WHERE`
* Sorting results using `ORDER BY`
* Extracting time information using `EXTRACT()`
* Ranking best and worst sellers using sorting and limiting results

Example query:

```sql
SELECT SUM(total_price) AS total_revenue
FROM pizza_sales;
```

---

## 📂 Project Structure

```
Pizza-Sale-Excel-Dashboard
│
├── dataset
│   └── pizza_sales_data.csv
│
├── sql
│   └── pizza_sales_queries.sql
│
├── dashboard
│   └── pizza_sales_excel_dashboard.xlsx
│
└── README.md
```

---

## 📷 Dashboard Preview

*(Add a screenshot of your dashboard here)*

---

## 📚 Skills Demonstrated

* Data Cleaning
* SQL Query Writing
* Data Aggregation
* Business Insight Generation
* Excel Dashboard Design

---

## 🚀 Future Improvements

* Build the dashboard in **Power BI or Tableau**
* Add **customer segmentation analysis**
* Perform **predictive sales analysis**


