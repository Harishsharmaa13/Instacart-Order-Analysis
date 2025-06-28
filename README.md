# 🛒 Instacart Order Behavior Analysis using PySpark

This project analyzes Instacart’s grocery order dataset to uncover meaningful customer purchasing patterns, reorder behaviors, and time-based trends. 
The goal is to turn raw transactional data into actionable business insights using scalable data engineering and visualization techniques.

---

## 📌 Project Goals

- Explore product-level trends and aisle distribution
- Understand user behavior: one-time vs repeat customers
- Analyze order sizes, reorder frequencies, and power users
- Visualize patterns by day of week and hour of day
- Provide strategic business recommendations

---

## 🛠️ Tech Stack

| Tool          | Purpose                           |
|---------------|------------------------------------|
| **PySpark**   | Distributed data processing         |
| **Pandas**    | Local data transformation           |
| **Seaborn**   | Data visualization (bar, line, KDE) |
| **Matplotlib**| Plots and chart enhancements        |
| **Jupyter**   | Notebook development environment    |
| **Parquet**   | Columnar storage format for fast I/O|

---

## 📂 Dataset

- Source: [Kaggle - Instacart Market Basket Analysis](https://www.kaggle.com/datasets/instacart/market-basket-analysis)
- Files used:
  - `orders.csv`
  - `products.csv`
  - `aisles.csv`
  - `departments.csv`
  - `order_products__prior.csv`
  - `order_products__train.csv`

---

## 📈 Key Analyses & Questions Answered

### 🔍 Product Insights
- Top 10 aisles and departments by product count
- Reorder rates per product and aisle

### 👥 Customer Behavior
- Basket size distribution
- One-time vs repeat buyers
- Top 10 most active users

### 🕒 Time-Based Patterns
- Orders by day of the week
- Orders by hour of the day
- Average order size by weekday

### 📦 Operational Patterns
- Reorder behavior by category
- Product distribution across departments and aisles

---

## 🧠 Insights Summary

Some key takeaways from the analysis:

- Over **60% of products** are reordered regularly, showing loyalty trends
- **Sunday and Monday** are peak order days
- Most users are **repeat buyers**, but **15% churn** after first order
- Baby products, Dairy, and Fresh Produce have **highest reorder probability**

→ See the full [INSIGHTS.md](INSIGHTS.md) report for business recommendations and future scope.
