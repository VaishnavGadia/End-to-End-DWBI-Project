# End-to-End DWBI Project: Real-Life Data Integration with Snowflake, Python, SQL & Power BI

## 📌 Overview
This project is a comprehensive end-to-end Data Warehouse & Business Intelligence (DWBI) solution that simulates real-world data integration workflows. It demonstrates how to extract data from an OLTP system, transform and load it into Snowflake, perform ad hoc SQL queries for analysis, and visualize insights using Power BI.

## 🚀 Motivation
In today's data-driven world, businesses rely on robust DWBI solutions for strategic decision-making. This project was built to:
- Connect the dots between OLTP systems, data warehousing, and business intelligence.
- Provide hands-on experience with Snowflake, SQL, Python, and Power BI.
- Simulate real-world data workflows, including data generation, extraction, transformation, and visualization.

## 🎯 Key Features
- **Simulated OLTP System**: Generates and extracts structured data using Python.
- **Snowflake Integration**: Loads, processes, and manages data efficiently.
- **SQL Analytics**: Executes 25+ ad hoc queries for business insights.
- **Power BI Dashboards**: Creates interactive visualizations for better decision-making.
- **Automated ETL Pipeline**: Uses Python scripts to generate, clean, and load data.

## 🏗️ Tech Stack
- **Python**: Data generation, ETL processes, and Snowflake integration.
- **Snowflake**: Cloud-based data warehousing.
- **SQL**: Ad hoc queries and transformations.
- **Power BI**: Data visualization and dashboarding.
- **Notepad++**: Scripting and code management.
- **Excel**: Reference data and schema validation.

## 🛠️ Implementation Steps
### 1️⃣ Data Generation
- Generate synthetic test data (customers, stores, products, transactions) using Python.
- Simulate an OLTP system using CSV files as a data source.

### 2️⃣ Data Extraction & Transformation
- Extract data from Oracle using Python.
- Store raw data in a staging area (CSV files).
- Transform data using Python and Pandas.

### 3️⃣ Data Loading into Snowflake
- Create Snowflake database, schemas, tables, and relations.
- Load data into Snowflake using **SnowSQL & COPY Command**.
- Perform integrity checks and apply constraints.

### 4️⃣ SQL Analytics & Reporting
- Execute **25+ analytical SQL queries** for insights.
- Perform aggregations, filtering, and business logic transformations.
- Implement data validation techniques.

### 5️⃣ Power BI Visualization
- Design a data model in Power BI.
- Create **interactive dashboards** with KPIs and trends.
- Implement **measures & calculated columns** for insightful reporting.

## 📊 Data Model
The project follows a **star schema** with:
- **Fact Table:** `fact_orders` (captures transactions and sales data).
- **Dimension Tables:** `dim_customer`, `dim_store`, `dim_product`, `dim_date`, `dim_loyalty_info`.

## 🔥 Challenges & Learnings
### Challenges
- Handling large datasets efficiently.
- Ensuring data consistency between OLTP and OLAP systems.
- Writing optimized SQL queries for analysis.

### Learnings
- Real-world ETL strategies with Python and Snowflake.
- Effective data modeling techniques.
- Creating powerful business insights using SQL and Power BI.

## 📢 How to Use
1. Clone this repository.
2. Set up your Snowflake account and database.
3. Run Python scripts to generate and extract data.
4. Load data into Snowflake using SnowSQL.
5. Execute SQL queries for analysis.
6. Connect Snowflake with Power BI and build dashboards.

## 🎯 Future Enhancements
- Implement CI/CD pipelines for automated data integration.
- Introduce orchestration tools like **Apache Airflow**.
- Expand dashboards with predictive analytics using **ML models**.

---

📧 **Connect with Me:** Feel free to reach out if you have questions or want to collaborate!

💡 Happy coding & data crunching!

