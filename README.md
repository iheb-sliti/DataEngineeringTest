# Azure Data Engineering Pipeline  

## 📌 Overview  
This project implements an **Azure Data Factory (ADF) pipeline** to:  
- Extract **Belgium holidays** and **currency exchange rates** from APIs.  
- Store the data in **Azure SQL Database**.  
- Transform USD rates into EUR.  
- Create a **SQL View (`exchange_rates`)** for unified reporting.  
- Automate deployments using **CI/CD (GitHub Actions)**.  

## 🚀 Technologies Used  
- **Azure Data Factory** (Data ingestion & transformation)  
- **Azure SQL Database** (Data storage & processing)  
- **Azure Blob Storage** (Staging layer)  
- **GitHub Actions** (CI/CD automation)  

## 🏗️ Solution Architecture  
1️⃣ **Pipelines:** Fetch & process API data.  
2️⃣ **Stored Procedure:** Convert USD to EUR.  
3️⃣ **SQL View:** Merge exchange rates with holidays.  
4️⃣ **CI/CD:** Automate ADF deployments.  

## 📊 Next Steps  
Run the pipelines, validate results, and automate deployments via CI/CD.  
