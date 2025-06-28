# 🛒 Instacart Market Basket Analysis (PySpark Project)

This project analyzes customer behavior and product trends from the Instacart dataset using **PySpark**, **Pandas**, and **Seaborn**. It focuses on four key business areas: product performance, customer engagement, time-based order patterns, and basket-level behavior.

---

## 📌 Objectives

- Identify top-selling products and aisles
- Analyze one-time vs repeat buyer behavior
- Discover ordering patterns by time/day
- Evaluate basket size and reorder behavior

---

## 🧠 Key Analysis Areas

### 1. 🛒 Product Performance Analysis
- Most popular products and aisles
- Reorder rates per product and aisle
- Inventory insights based on product distribution

### 2. 👥 Customer Behavior Analysis
- One-time vs repeat customer ratio
- Power user behavior (top users by order count)
- Retention trends and engagement patterns

### 3. ⏰ Order Pattern & Time-Based Analysis
- Orders by day of week & hour of day
- Peak shopping periods
- Weekly order size comparison

### 4. 🧺 Basket / Cart Behavior Analysis
- Distribution of products per order
- Basket size by day of the week
- Category-wise contribution to basket contents

---

## 🛠️ Tech Stack

| Tool          | Usage                              |
|---------------|-------------------------------------|
| PySpark       | Big data processing and aggregation |
| Pandas        | Data manipulation and joins         |
| Seaborn       | Visualization (bar, KDE, line)      |
| Matplotlib    | Chart customization                 |
| Jupyter       | Development environment             |
| Parquet       | Efficient file format (optional)    |

---

## 📁 Dataset

- 📦 Source: [Kaggle - Instacart Market Basket](https://www.kaggle.com/competitions/instacart-market-basket-analysis/data)
- Files used:
  - `orders.csv`
  - `products.csv`
  - `aisles.csv`
  - `departments.csv`
  - `order_products__prior.csv`
  - `order_products__train.csv`

---

## 📈 Results

- Over **60%** of products are reordered — strong brand loyalty
- **Sunday and Monday** are the most popular days to shop
- Most orders contain **6 to 12 products**
- High-frequency users show consistent engagement and large order counts

👉 See full insights in [`INSIGHTS.md`](INSIGHTS.md)

---

## ▶️ How to Run

```bash
# Clone the repository
git clone https://github.com/your-username/instacart-analysis.git
cd instacart-analysis

# (Optional) Create virtual environment
conda create -n bigdata_env python=3.9
conda activate bigdata_env
pip install -r requirements.txt

# Launch notebook
jupyter notebook notebooks/Instacart_EDA.ipynb

