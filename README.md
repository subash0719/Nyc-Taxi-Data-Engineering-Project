# 🚖 NYC Taxi Data Engineering Project

![Data Engineering](https://img.shields.io/badge/Data%20Engineering-%F0%9F%9A%80-blue)
![Azure](https://img.shields.io/badge/Azure-ADLS%20%7C%20ADF%20%7C%20Databricks-0089D6)
![Power BI](https://img.shields.io/badge/Visualization-Power%20BI-yellow)

## 📌 Overview
This project demonstrates a **scalable data pipeline** using **Microsoft Azure** to process and analyze NYC taxi data. The pipeline follows the **Medallion Architecture (Bronze, Silver, Gold)**, leveraging **Azure Data Factory (ADF), Azure Data Lake Storage (ADLS), Databricks, and Power BI**.

---

## 🚀 Tech Stack & Tools

| Technology    | Purpose |
|--------------|---------|
| **ADF (Azure Data Factory)** | Data ingestion from NYC Taxi Web API & GitHub CSVs |
| **ADLS (Azure Data Lake Storage)** | Stores raw & processed data (Bronze, Silver, Gold) |
| **Microsoft Entra ID** | Secure authentication for accessing ADLS from Databricks |
| **Databricks** | Data transformation and Delta Table creation |
| **Power BI** | Data visualization and analytics |

---

## 🔄 Data Pipeline Architecture

🚕 NYC Taxi API / GitHub CSVs 
   ⬇ (Ingest via ADF)
🛢 ADLS - Bronze Layer (Raw Data)
   ⬇ (Processing in Databricks)
🪙 ADLS - Silver Layer (Cleaned & Processed Data)
   ⬇ (Transformation & Delta Table Creation)
💰 ADLS - Gold Layer (Optimized Data for Analysis)
   ⬇ (Connected to Power BI)
📊 Power BI Dashboard

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
✅ End-to-end **data pipeline automation** with ADF & Databricks  
✅ **Medallion Architecture** implementation for structured processing  
✅ Secure authentication with **Microsoft Entra ID**  
✅ **Optimized Delta Tables** for faster querying in Power BI  

---

## 🔚 Conclusion
This project showcases an **end-to-end data engineering workflow**, leveraging **Azure Data Factory, ADLS, Databricks, and Power BI**. By implementing the **Medallion Architecture**, the pipeline ensures a structured approach to data ingestion, transformation, and analysis. This setup not only enables **scalability and performance optimization** but also ensures **security with Microsoft Entra ID authentication**. 

---

🚀 **Happy Coding!**

