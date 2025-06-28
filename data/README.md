# 📦 Instacart Dataset Information

The full dataset used in this project is too large to be hosted on GitHub.

## 📌 Why data is not included?
- The raw and processed files exceed GitHub's individual file size limits (100MB).
- To maintain repo efficiency and avoid storage issues.

## 📥 How was the data obtained?
- Extracted from a **MySQL** database using SQL queries
- Exported as `.csv` files and converted to `.parquet` format for faster processing in PySpark

## 📂 What does the dataset include?
- `aisles.csv` – Aisle ID and names  
- `departments.csv` – Department ID and names  
- `products.csv` – Product info including IDs, names, aisle and department  
- `orders.csv` – Order-level information  
- `order_products_prior.csv` – Prior order details  
- `order_products_train.csv` – Train order details  

## 🔗 Public Dataset Link
If you'd like to work with the same data, you can download it from the original source:

➡️ [Instacart Market Basket Analysis Dataset](https://www.instacart.com/datasets/grocery-shopping-2017)

## 🛠 Suggested Usage
- Place your downloaded files inside this `/data` folder
- Make sure file names match those used in the notebook (e.g., `orders.csv`, `products.csv`)
