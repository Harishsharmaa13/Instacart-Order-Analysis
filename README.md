Instacart Market Basket Analysis using PySpark & Pandas
This project showcases an end-to-end data analysis workflow on Instacart order data. The data was initially stored in SQL Server, extracted using SQL queries, downloaded as .csv files, and then imported into Python for further processing. To handle large datasets efficiently, the data was converted into Parquet format and processed using PySpark.

📌 Objectives
Understand product reorder behavior and top-selling categories

Analyze customer order habits by time, basket size, and frequency

Identify one-time vs repeat buyers and power users

Provide actionable business insights based on historical order data

📥 Data Flow & Processing
Data Source: Extracted from Microsoft SQL Server using SQL Server Management Studio (SSMS)

Data Export: Exported relational tables as .csv files to local system

Data Optimization: Converted .csv files into .parquet format for faster loading and processing

Processing Tool: Used PySpark for large-scale data manipulation and aggregation

Visualization & Insights: Used Pandas, Seaborn, and Matplotlib for plotting and analysis

🧠 Key Analysis Areas
1. 🛒 Product Performance Analysis
Top reordered products & aisles

Product count per aisle/department

Reorder rate by aisle

2. 👥 Customer Behavior Analysis
One-time vs Repeat buyers

Top users by number of orders

Power users & their patterns

3. ⏰ Time-Based Order Analysis
Orders by day of week and hour of day

Average order size by day

Weekly behavior insights

4. 🧺 Basket Behavior Analysis
Order size distribution

Basket size trends by day

Products per basket and reorder frequency

🛠️ Tech Stack
Tool	Purpose
SQL Server	Original data source (extraction)
PySpark	Large-scale data processing
Pandas	Data manipulation & cleaning
Seaborn	Data visualization
Matplotlib	Chart customization
Jupyter	Development environment


📈 Sample Insights
🌀 Over 60% of products are reordered → Strong repeat behavior

📦 Most baskets contain 6–12 items

⏱️ Sunday and Monday are the most active shopping days

🧍 10% of users place over 50 orders → valuable repeat customers

Read full insights in INSIGHTS.md



