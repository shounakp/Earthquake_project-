# 🌍 Earthquake Data Engineering Project (Microsoft Fabric)

This project demonstrates an **end-to-end data engineering pipeline** built using **Microsoft Fabric**. It leverages the **USGS Earthquake API** to ingest, transform, and visualize real-time earthquake data.

---

## 📌 Objective

Build a full-stack data solution in **Microsoft Fabric** that:
- Ingests real-time data from the USGS Earthquake API
- Transforms and enriches data using **Data Engineering Notebooks**
- Orchestrates workflows using **Data Factory Pipelines**
- Visualizes insights using **Power BI**

---

## 🛠️ Technologies Used

| Layer            | Tools |
|------------------|-------|
| Data Ingestion   | Microsoft Fabric Dataflow Gen2 |
| Data Processing  | Lakehouse, PySpark Notebooks |
| Orchestration    | Microsoft Fabric Data Factory |
| Visualization    | Power BI |
| Storage          | OneLake |
| Source API       | [USGS Earthquake API](https://earthquake.usgs.gov/fdsnws/event/1/) |

---

## 📁 Project Structure

Earthquake_project-/
│
├── notebooks/
│ └── extract_transform_earthquake_data.ipynb
│
├── pipelines/
│ └── earthquake_etl_pipeline.json
│
├── reports/
│ └── Earthquake_PowerBI_Report.pbip
│
├── lakehouse/
│ └── earthquake_curated.parquet
│
└── README.md
