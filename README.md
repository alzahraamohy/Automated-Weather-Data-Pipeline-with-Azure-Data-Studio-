# End-to-End Data Engineering: Automated Weather Data Pipeline with SQL Server & Azure Data Studio 🌦️

Data engineering is at the heart of modern analytics, and building a well-structured **ETL pipeline** is a critical skill. To get hands-on experience, I built an **automated weather data pipeline** using **Azure Data Studio, SQL Server, and Python**.

This project **extracts**, **processes**, **stores**, **analyzes**, and **visualizes** real-time weather data, just like a production-level data pipeline!

## 📌 How the Pipeline Works (Workflow Overview)

### Step 1: Extracting Data (E - Extract)
- Fetches real-time weather data from the **OpenWeatherMap API** using Python’s `requests` library.
- Data includes **city name, temperature, humidity, weather conditions, and timestamps**.

### Step 2: Storing Data in SQL Server (T - Transform & Load)
- Data is cleaned and formatted before insertion.
- The data is stored in **SQL Server (MSSQL) using Azure Data Studio**.
- The schema is designed to capture key weather attributes for historical analysis.

### Step 3: Processing & Transforming Data
- Uses **Pandas** to process and clean the data.
- Converts timestamps and applies transformations (e.g., converting temperature from Celsius to Fahrenheit).
- Performs basic **data quality checks** before analysis.

### Step 4: Analyzing & Visualizing Data
- loads data into **Power BI** for a dynamic dashboard with interactive filters.

### Step 5: Automating the Pipeline
- Schedules the Python script using **Windows Task Scheduler** or **Azure Data Factory** to run daily.
- Ensures continuous data ingestion without manual intervention.

## 📌 Tech Stack Used
- 💡 **SQL Server + Azure Data Studio** → Database storage & query execution
- 💡 **Python (requests, pandas, pyodbc)** → API calls, data transformation, and ingestion
- 💡 **Matplotlib / Power BI** → Data visualization & trend analysis
- 💡 **Windows Task Scheduler / Azure Data Factory** → Pipeline automation


