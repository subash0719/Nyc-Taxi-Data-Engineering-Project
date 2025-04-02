# 🚖 NYC Taxi Data Engineering Project

![Data Engineering](https://img.shields.io/badge/Data%20Engineering-%F0%9F%9A%80-blue)
![Azure](https://img.shields.io/badge/Azure-ADLS%20%7C%20ADF%20%7C%20Databricks-0089D6)
![Power BI](https://img.shields.io/badge/Visualization-Power%20BI-yellow)

## 📌 Overview
This project demonstrates a **scalable data pipeline** using **Microsoft Azure** to process and analyze NYC taxi data. Following the **Medallion Architecture (Bronze, Silver, Gold)** framework, this workflow strategically integrates **Azure Data Factory (ADF), Azure Data Lake Storage (ADLS), Databricks, and Power BI** to ensure scalability, security, and analytical efficiency.

---

## 🚀 Tech Stack & Tools

| 🛠 **Technology**    | 🔍 **Purpose** |
|--------------------|--------------|
| ⚙️ **ADF (Azure Data Factory)** | Automates data ingestion from the NYC Taxi Web API & GitHub CSVs |
| 🛢 **ADLS (Azure Data Lake Storage)** | Provides a scalable storage solution for raw, processed, and analytical data |
| 🔐 **Microsoft Entra ID** | Ensures secure authentication and access management for Databricks and ADLS |
| 🔥 **Databricks** | Supports advanced data transformation, ETL processes, and Delta Table management |
| 📊 **Power BI** | Enables interactive data visualization and business intelligence insights |

---

## 🔄 Data Pipeline Architecture

1️⃣ **Data Ingestion**
   - 🏗 **Sources:** NYC Taxi Web API (Parquet files) & GitHub CSVs  
   - 🚀 Data is ingested into **ADLS (Bronze Layer)** via **Azure Data Factory (ADF)**  
   ⬇

2️⃣ **Data Processing & Transformation**
   - 🔑 **Microsoft Entra ID** ensures secure authentication for **Databricks**  
   - 🏗 Raw data undergoes **cleaning, validation, and structuring** into the **Silver Layer**  
   - 🛠 Transformation logic is applied to create **optimized Delta Tables** in the **Gold Layer**  
   ⬇

3️⃣ **Data Visualization & Insights**
   - 📡 **Gold Layer Delta Tables** are directly connected to **Power BI**  
   - 📊 Advanced **interactive dashboards** provide actionable business insights  


![NycTaxiArch](https://github.com/user-attachments/assets/06654f39-c2c2-4975-be72-fa0a954d176d)

---

## ⚙️ Implementation Steps

### 1️⃣ **Data Ingestion**
- Pulled **Parquet files** from **NYC Taxi Web API**
- Extracted **CSV files** from **GitHub**
- Used **ADF** to load data into **ADLS (Bronze Layer)**

### 2️⃣ **Data Processing & Transformation**
- Created **Databricks App in Microsoft Entra ID** for secure access
- Processed raw data into structured format (**Silver Layer**)
- Converted into **Delta Tables** in the **Gold Layer**

### 3️⃣ **Data Visualization**
- Connected **Gold Layer Delta Tables** to **Power BI**
- Created **interactive dashboards** for deeper insights

---

## 📌 Key Takeaways
✅ **Automated, end-to-end data pipeline** with ADF & Databricks  
✅ **Structured Medallion Architecture** for optimized data processing  
✅ 🔐 **Secure authentication and access management** via Microsoft Entra ID  
✅ 🚀 **Performance-optimized Delta Tables** for seamless Power BI integration 

---

## 🔚 Conclusion
This project showcases an **end-to-end data engineering workflow**, leveraging **Azure Data Factory, ADLS, Databricks, and Power BI**. By implementing the **Medallion Architecture**, the pipeline ensures a structured approach to data ingestion, transformation, and analysis. This setup not only enables **scalability and performance optimization** but also ensures **security with Microsoft Entra ID authentication**. 

---

🚀 **Happy Coding!**

