# 📊 SQL Analytics

This repository contains my SQL practice focused on **data analysis and real-world problem solving**.
The goal is to build strong querying skills required for Data Science and Data Analyst roles.

---

## 🚀 Objectives

* Strengthen SQL fundamentals
* Practice real-world data analysis queries
* Improve problem-solving using structured data
* Build a consistent learning habit

---

## 🧠 Topics Covered

* SELECT statements
* WHERE, ORDER BY, LIMIT
* GROUP BY & Aggregations
* Joins (INNER, LEFT, RIGHT)
* Subqueries
* Basic Data Cleaning

---



---

## 📌 Sample Queries

### 🔹 Total Revenue
```sql
SELECT SUM(quantity * price) AS revenue
FROM sales;
```

### 🔹 Top Selling Product

```sql
SELECT product, SUM(quantity) AS total_sold
FROM sales
GROUP BY product
ORDER BY total_sold DESC;
```

---

## 🎯 Goal

To transition from basic SQL queries to **advanced data analysis and real-world datasets**, and prepare for Data Science roles.

---

## ⚡ Progress

* [ ] Basics
* [ ] Aggregations
* [ ] Joins
* [ ] Subqueries
* [ ] Real-world datasets

---

## 🤝 Connect

This repository is part of my learning journey in Data Science.
Consistent updates will be added as I progress 🚀
