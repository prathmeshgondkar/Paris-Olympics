# 🏅 Paris 2024 Olympics – End-to-End Data Analytics Pipeline on Azure

A full-scale, cloud-native data project built to simulate and analyse the Paris 2024 Olympics using Microsoft Azure. This end-to-end pipeline covers everything from data ingestion to dashboarding, integrating tools like **Azure Data Factory**, **Databricks**, **Synapse Analytics**, **Power BI**, **Python**, and **Apache Spark**.

> 💡 Built as a portfolio-grade project to demonstrate real-world data engineering, project orchestration, and cloud architecture skills.

---

## 🚀 Project Goals

- Build a complete Azure data pipeline for Olympic analytics
- Simulate datasets using a mix of synthetic (ChatGPT) and real-world (Kaggle) data
- Design a cross-region architecture for latency and cost optimisation
- Transform and analyse data using Spark and SQL
- Create interactive dashboards with Power BI for insights

---

## 🧰 Tools & Technologies

|      Layer        |                 Tools / Skills                          |
|-------------------|---------------------------------------------------------|
| Ingestion         | Azure Data Factory                                      |
| Storage           | Azure Data Lake Storage Gen2                            |
| Transformation    | Azure Databricks (Apache Spark, PySpark)                |
| Aggregation       | Azure Synapse Analytics (Serverless SQL)                |
| Visualisation     | Power BI, Excel                                         |
| Languages Used    | Python, SQL, DAX                                        |
| Project Skills    | Orchestration, Cross-Region Design, Cost Optimisation   |

---

## 🗂️ Data Sources

- 🧠 **90% Synthetic Data** generated using ChatGPT (e.g., athletes, coaches, medals, entries by gender)
- 📊 **10% Real Data** from Kaggle (e.g.teams)
- 🔗 Pulled from GitHub using Azure Data Factory pipelines

---

## 📍 Architecture Overview
- Data Source (ChatGPT + Kaggle via GitHub)
- Azure Data Factory (Ingestion & Orchestration)
- Azure Data Lake Gen2 (Raw Zone)
- Azure Databricks (PySpark Processing & Transformation)
- Azure Data Lake Gen2 (Transformed Zone)
- Azure Synapse Analytics (SQL Aggregation)
- Power BI (Interactive Dashboards)

  ![Pipeline ](https://github.com/prathmeshgondkar/Paris-Olympics/blob/3401a0faed672e8f28c75cecb95d8903e68514df/Pipeline.png) 


🌐 Cross-region deployment:  
> • Data Factory → Southeast Asia  
> • Databricks & Data Lake → Canada Central

---

## 🔍 Power BI Dashboards

![Power BI Dashboard](https://github.com/prathmeshgondkar/Paris-Olympics/blob/864735cfa064f538308429bda4058b4ca17aac46/Dashboard.png) 

Key visualisations:
- 👥 Participation by Gender and Sport
- 🥇 Medal Tally by Country
- 🗺️ Country-wise Distribution (Map View)
- 🏃 Number of Teams per Country

> Dashboards are dynamic with filters, tooltips, and drilldowns.

---

## 🌍 Cross-Region Architecture

| Component            | Azure Region      |
|---------------------|--------------------|
| Azure Data Factory   | Southeast Asia    |
| Databricks           | Central Canada    |
| Data Lake Gen2       | Central Canada    |

📌 This setup demonstrates:
- Handling **latency** between ingestion and processing
- Planning for **data egress costs**
- Designing real-world, **globally distributed pipelines**

---

## ✅ Features & Highlights

- ⛓️ Fully automated, modular pipeline with zero manual intervention
- 🧠 PySpark + SQL for scalable, clean transformations
- 🗃️ Organised data zones (Raw vs Transformed)
- 🧩 Seamless integration between Azure services
- 📊 Power BI dashboards tailored for decision-makers
- 🔄 Ready for refresh scheduling and scaling

---

## 🧠 Key Learnings & Skills Demonstrated

- 📦 End-to-end Azure data engineering
- ⚙️ Workflow design with Azure Data Factory
- 🔥 Big data transformation using Databricks (Apache Spark)
- 🧮 Data modelling and analysis in Synapse SQL
- 🎨 Dashboard development with Power BI
- 🌐 Cloud cost management and cross-region thinking
- 🔐 Secure access, automation, and resource control

---

## 📬 Access & Contact

Interested in the code, pipeline JSONs, or a walkthrough?

📩 **Get in touch via [LinkedIn](www.linkedin.com/in/prathmeshgondkar)

---

## ⭐ Like This Project?

If this helped or inspired you, consider starring ⭐ this repository.

---
