# 🌍 Earthquake Data Engineering Project with Microsoft Fabric

## 📌 Project Overview
This project demonstrates how to build an **end-to-end data engineering and analytics pipeline** using **Microsoft Fabric**. It covers data ingestion, transformation, and visualization using Fabric’s **Data Factory**, **Data Engineering**, and **Power BI** experiences.

The pipeline ingests **global earthquake events data from the USGS API**, processes it through **Bronze, Silver, and Gold layers**, and prepares it for analytical reporting.

---

## 🚀 Key Features
- End-to-end data pipeline using Microsoft Fabric
- Ingestion of real-world earthquake data from **USGS**
- Medallion architecture (Bronze → Silver → Gold)
- Business-ready datasets for Power BI reporting

---

## 🛠 Technologies Used
- **Python**
- **PySpark**
- **Microsoft Fabric**
  - Data Engineering
  - Data Factory
  - Power BI

---

## 📂 Repository Contents

### 🥉 Bronze Layer – Raw Data Ingestion
**Worldwide Earthquake Events API – Bronze Layer Processing**

- Ingests raw earthquake event data from the **USGS API**
- Applies minimal transformations
- Stores data in its original structure
- Serves as the foundation for downstream processing

---

### 🥈 Silver Layer – Data Cleansing & Transformation
**Worldwide Earthquake Events API – Silver Layer Processing**

- Cleans and standardizes Bronze layer data
- Handles missing and inconsistent values
- Transforms and consolidates datasets
- Prepares data for analytical use

---

### 🥇 Gold Layer – Business-Ready Data
**Worldwide Earthquake Events API – Gold Layer Processing**

- Refines data into analytics-ready datasets
- Optimized for reporting and visualization
- Designed for consumption in **Power BI**
- Enables high-value insights and decision-making

---

## 📊 Data Attribute Definitions

| Attribute | Description |
|---------|------------|
| `id` | Unique string identifier for each earthquake event |
| `latitude` | Latitude of the event (double) |
| `longitude` | Longitude of the event (double) |
| `elevation` | Elevation of the event in meters (double) |
| `title` | Title or name of the earthquake event |
| `place_description` | Description of the event location |
| `sig` | Significance score of the event (bigint) |
| `mag` | Earthquake magnitude (double) |
| `magType` | Type of magnitude scale used |
| `time` | Timestamp of the earthquake event |
| `updated` | Timestamp of the last data update |

---

## ✅ Prerequisites
- Microsoft Fabric account
- Fabric Administrator access (or access via an Admin user)
- Basic knowledge of:
  - Python
  - Apache Spark
  - Data Engineering concepts
- Basic Power BI skills

---

## 📈 Output & Visualization
The final Gold layer datasets are designed to be directly consumed by **Power BI Semantic Models** for building interactive dashboards and analytical reports.
