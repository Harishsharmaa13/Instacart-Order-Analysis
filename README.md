# Instacart Market Basket Analysis using PySpark & Pandas
This project showcases an end-to-end data analysis workflow on Instacart order data. The data was initially stored in MySQL, extracted using SQL queries, downloaded as .csv files, 
and then imported into Python for further processing. To handle large datasets efficiently, the data was converted into Parquet format and processed using PySpark.

## 📌 Objectives
- Understand product reorder behavior and top-selling categories

- Analyze customer order habits by time, basket size, and frequency

- Identify one-time vs repeat buyers and power users

- Provide actionable business insights based on historical order data

## 📥 Data Flow & Processing
- Data Source: Extracted from MySQL using SQL queries

- Data Export: Saved relational tables as .csv files on local machine

- Data Optimization: Converted .csv files into .parquet format for faster loading

- Processing Tool: Used PySpark for scalable data transformation and analysis

- Visualization: Used Pandas, Seaborn, and Matplotlib for plots and summaries

⚠️ Due to the large size of the dataset, the actual data files are not included in this repository. Refer to the data/README.md for download instructions.

## 🧠 Key Analysis Areas
1. 🛒 Product Performance Analysis

- Top reordered products & aisles

- Product count per aisle/department

- Reorder rate by aisle

2. 👥 Customer Behavior Analysis
   
- One-time vs Repeat buyers

- Top users by number of orders

- Power users & their patterns

3. ⏰ Time-Based Order Analysis

- Orders by day of week and hour of day

- Average order size by day

- Weekly behavior insights

4. 🧺 Basket Behavior Analysis
   
- Order size distribution

- Basket size trends by day

- Products per basket and reorder frequency

## 🛠️ Tools & Technologies

| Tool            | Purpose                                                                 |
|-----------------|-------------------------------------------------------------------------|
| **MySQL**       | Data storage and extraction using SQL queries                           |
| **PySpark**     | Scalable big data processing & transformation                           |
| **Pandas**      | Data manipulation and preprocessing in Python                           |
| **Matplotlib**  | Plotting basic and customized visualizations                            |
| **Seaborn**     | Advanced and statistical data visualizations                            |
| **Jupyter**     | Interactive environment for analysis and coding                         |
| **Parquet**     | Optimized data storage format for faster I/O with columnar efficiency   |


## 📈 Sample Insights
- 🌀 Over 60% of products are reordered → strong repeat behavior

- 📦 Most baskets contain 6–12 items

- ⏱️ Sunday and Monday are the most active shopping days

- 🧍 Top 10% of users place 50+ orders → highly engaged customers

## 📝 Read full insights in INSIGHTS.md





