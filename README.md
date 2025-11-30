# SQL Exploratory Data Analysis (EDA) on Sales Data

This project demonstrates **Exploratory Data Analysis (EDA)** using **SQL** on a retail sales database (`gold` schema).  
It covers database exploration, dimensional analysis, measures, magnitude comparisons, and ranking insights.

---

## 📊 Project Overview
The goal of this project is to:
- Explore database structure and metadata
- Analyze customer demographics and product categories
- Investigate sales trends over time
- Compute key business metrics (sales, orders, customers, products)
- Compare performance across categories, countries, and genders
- Rank top and bottom performing products

---

## 🗂️ Dataset Structure
The project uses three main tables:
- **`dim_customers`** → Customer demographics (country, gender, birthdate, etc.)
- **`dim_products`** → Product details (category, subcategory, cost, etc.)
- **`fact_sales`** → Transactional sales data (order_date, sales_amount, quantity, price)

---

## 🔍 Analysis Steps
1. **Database Exploration**  
   - Inspect tables and columns using `INFORMATION_SCHEMA`

2. **Dimensions Exploration**  
   - Countries, product categories, subcategories, product names

3. **Date Exploration**  
   - First and last order dates, order range in years  
   - Youngest and oldest customers

4. **Measures Exploration**  
   - Total sales, total items sold, average price  
   - Number of orders, products, and customers

5. **Business Metrics Report**  
   - Unified report of KPIs using `UNION ALL`

6. **Magnitude Analysis**  
   - Customers by country and gender  
   - Products by category  
   - Average costs and revenue by category  
   - Revenue by customer  
   - Distribution of items sold across countries

7. **Ranking Analysis**  
   - Top 5 products by revenue  
   - Bottom 5 products by revenue

---

## 📈 Key Insights
- Identify **top-performing categories and products**
- Understand **customer demographics** driving sales
- Track **sales trends over time**
- Highlight **business KPIs** for decision-making

---
-Run the SQL scripts in your preferred SQL environment (e.g., SQL Server, Azure Data Studio).

##🛠️ Tech Stack
- SQL Server (T-SQL)
- Relational Database Concepts
- Business Intelligence & Analytics

## 👤 AuthorWickliff
Focused on data engineering, SQL, and analytics for Kenya’s fintech and digital sectors.

