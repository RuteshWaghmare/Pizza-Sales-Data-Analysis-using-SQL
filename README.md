# 🍕 Pizza Sales Data Analysis (SQL)

## 📌 Project Overview
This project performs an end-to-end **sales data analysis for a fictional pizza restaurant** using **MySQL**.  
The goal is to convert raw transactional data into **actionable business insights** that help improve revenue, operations, and customer understanding.

This project demonstrates strong skills in:
- SQL data analysis
- Business problem solving
- Data-driven decision making

---

## 🎯 Business Objective
The objective of this analysis is to help the business answer critical questions such as:

- Which pizzas generate the highest revenue?
- What are the peak order times and days?
- Which categories and sizes are most preferred by customers?
- How is revenue growing over time?

---

## ❓ Key Business Questions Solved

### 🔹 Basic Level
- Total number of orders placed  
- Total revenue generated  
- Highest-priced pizza  

### 🔹 Intermediate Level
- Most commonly ordered pizza size  
- Category-wise distribution of pizzas  
- Hourly order distribution (peak demand analysis)  

### 🔹 Advanced Level
- Revenue contribution by each pizza type (%)  
- Cumulative revenue over time (growth tracking)  
- Top 3 pizzas by revenue within each category using ranking  

---

## 📂 Dataset Description
The dataset is structured into a **relational database with 4 tables**:

### 1. orders
- order_id  
- order_date  
- order_time  

### 2. order_details
- order_details_id  
- order_id  
- pizza_id  
- quantity  

### 3. pizzas
- pizza_id  
- pizza_type_id  
- size  
- price  

### 4. pizza_types
- pizza_type_id  
- name  
- category  
- ingredients  

👉 These tables are connected using primary and foreign key relationships.

---

## 🛠 Tools & Technologies Used
- SQL (MySQL) – Data extraction and analysis  
- Database Design – Relational schema understanding  

### Core SQL Concepts Used:
- JOINs (INNER, LEFT)  
- Aggregate Functions (SUM, COUNT, AVG)  
- Window Functions (RANK() OVER)  
- Date & Time Functions  

---

## ⚙️ Approach / Methodology

### 1. Data Integration
- Joined multiple tables to connect orders, pizzas, and categories  

### 2. Data Aggregation
- Converted raw transaction data into KPIs like:
  - Total revenue  
  - Total orders  
  - Average daily demand  

### 3. Time-Based Analysis
- Identified:
  - Peak ordering hours  
  - Daily sales trends  

### 4. Advanced Analysis
- Used window functions to:
  - Rank pizzas within categories  
  - Identify top-performing products  

---

## 📊 Key Insights

- Revenue was calculated using quantity × price across all orders  
- Identified top-selling pizzas and most profitable categories  
- Peak order times were found for staffing optimization  
- Most popular pizza sizes were discovered  
- Cumulative revenue showed steady growth over time  

---

## 📈 Sample Outputs Generated
- Top 3 revenue-generating pizzas in each category  
- Category-wise pizza demand distribution  
- Average number of pizzas ordered per day  
- Cumulative revenue growth over time  

---

## 💼 Business Impact
This analysis helps the business:

- Improve menu optimization by focusing on high-performing pizzas  
- Optimize staffing during peak hours  
- Understand customer preferences better  
- Track revenue growth trends  
- Enable data-driven decision making  

---

## 📌 Conclusion
This project demonstrates how **SQL transforms raw transactional data into meaningful business insights**.

It highlights:
- Strong analytical thinking  
- SQL proficiency  
- Real-world business problem solving  

---

## 🚀 Skills Demonstrated (Interview Ready)
- SQL Data Analysis (Advanced Level)  
- Relational Database Understanding  
- Business Problem Solving  
- KPI Creation from Raw Data  
- Window Functions & Aggregations  
- Analytical Thinking  
