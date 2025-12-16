# US-Emission-Analysis-with-Databricks-
End-to-end data analysis on US emissions using Databricks SQL and interactive dashboards.


## 📌 Project Overview
This project analyzes United States emission data using Databricks,
leveraging SQL analytics and interactive dashboards to uncover trends
across years, continental, and emission sectors.

## 🛠 Tech Stack
- Databricks
- Apache Spark
- Databricks SQL
- SQL Analytics
- Python
- GitHub

## 📊 Data Source
- US Environmental Protection Agency (EPA)
- Kaggle / Government Open Data


## 🔄 Data Pipeline
1. Data ingestion into Databricks
2. Data cleaning and transformation using Spark
3. SQL-based analytical queries
4. Dashboard creation using Databricks SQL

## 📈 Key Insights
- Emission of Continental US 
- Emission vs Population
- Sum of Total emissions
- Total Emission by mTons of CO2e

## 🧪 Sample SQL Query
```sql
SELECT state, SUM(emission) AS total_emission
FROM emissions
GROUP BY state
ORDER BY total_emission DESC;
