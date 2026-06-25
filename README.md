# 🚚 Delhivery Logistics Feature Engineering & Route Performance Analysis

### End-to-End Feature Engineering, Exploratory Data Analysis (EDA), and Logistics Performance Analysis using Python

This project analyzes **Delhivery's logistics operations dataset** to transform raw shipment-level records into an analytics-ready dataset through **data cleaning, feature engineering, aggregation, exploratory data analysis (EDA), statistical validation, and business insight generation**.

The analysis evaluates delivery performance, compares actual delivery metrics against routing estimates (OSRM), identifies operational inefficiencies, and provides actionable recommendations that can improve **route planning, ETA prediction, logistics optimization, and operational decision-making.**

---

<p align="center">

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-013243?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Visualization-4C72B0)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Feature%20Engineering-F7931E?logo=scikitlearn)

</p>

---

## 📄 Project Deliverables

| Resource | Description |
|----------|-------------|
| 📓 **[Jupyter Notebook](https://github.com/Richa-Jain108/delhivery-logistics-feature-engineering-analysis/blob/main/notebooks/delhivery_logistics_feature_engineering_analysis.ipynb)** | Complete Python implementation including data cleaning, feature engineering, EDA, statistical analysis, and business insights |
| 📑 **[Analysis Report (PDF)](https://github.com/Richa-Jain108/delhivery-logistics-feature-engineering-analysis/blob/main/reports/delhivery_analysis_report.pdf)** | Comprehensive business report containing methodology, visualizations, findings, and recommendations |
| 📊 **[Dataset](https://d2beiqkhq929f0.cloudfront.net/public_assets/assets/000/001/551/original/delhivery_data.csv?1642751181)** | Original Delhivery logistics dataset |

---

# 🚀 Project Highlights

- 🚚 End-to-End Logistics Analytics & Feature Engineering Project
- 📦 Processed **144,867 Shipment-Level Records**
- 🔄 Aggregated Shipment-Level Data into Analytics-Ready Trip-Level Records
- 🧹 Extensive Data Cleaning, Validation & Preprocessing
- ⚙️ Business Feature Engineering Pipeline
- 📊 Exploratory Data Analysis (EDA)
- 📉 Missing Value Treatment & Outlier Detection (IQR Method)
- 🔢 Feature Encoding & Standardization
- 📈 Statistical Validation & Delivery Performance Analysis
- 🛣️ Actual vs OSRM Route Performance Comparison
- 💼 Actionable Business Insights & Logistics Recommendations

---

# 📌 Business Problem

## About Delhivery

Delhivery is India's largest fully integrated logistics company, operating across freight transportation, warehousing, and supply chain services.

The Data Science team receives raw shipment-level operational data from logistics pipelines. Before this data can be used for forecasting, optimization, reporting, or machine learning, it must first be cleaned, validated, aggregated, and transformed into meaningful business features.

This project focuses on preparing an analytics-ready logistics dataset while uncovering operational insights hidden within raw shipment records.

---

# 🎯 Project Objectives

This project answers the following business questions:

- How can shipment-level records be transformed into trip-level analytics?
- How closely do actual delivery times align with OSRM route estimates?
- What operational differences exist between FTL and Carting shipments?
- Which engineered features improve downstream analytics?
- How do missing values and outliers affect logistics data quality?
- Which operational metrics contribute most to delivery delays?
- How can Delhivery improve logistics efficiency using data?

---

# 📊 Dataset Overview

| Attribute | Details |
|------------|----------|
| **Industry** | Logistics & Supply Chain |
| **Dataset** | Delhivery Logistics Operations |
| **Records** | 144,867 Shipment Records |
| **Final Dataset** | Aggregated Trip-Level Dataset |
| **Features** | 24+ Operational Variables |
| **Objective** | Feature Engineering & Logistics Analytics |

---

# 🔄 Project Workflow

```text
Raw Shipment Data
        │
        ▼
Data Understanding & Validation
        │
        ▼
Data Cleaning & Missing Value Treatment
        │
        ▼
Shipment-to-Trip Aggregation
        │
        ▼
Feature Engineering
        │
        ▼
Exploratory Data Analysis (EDA)
        │
        ▼
Statistical Validation
        │
        ▼
Business Insights
        │
        ▼
Business Recommendations
```

---

# 🛠️ Tech Stack

### Programming

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-Learn
- Jupyter Notebook

---

# 🔍 Methodology

## 1️⃣ Data Understanding

- Dataset inspection
- Data type validation
- Statistical summary
- Duplicate analysis

### 2️⃣ Data Cleaning

- Missing value treatment
- Datatype optimization
- Memory optimization
- Removal of unnecessary variables

### 3️⃣ Feature Engineering

- Shipment-to-trip aggregation
- Source & destination parsing
- City & State extraction
- Datetime feature creation
- Delivery duration calculation

### 4️⃣ Data Preprocessing

- Outlier Detection (IQR Method)
- Feature Encoding
- Feature Scaling
- Standardization

### 5️⃣ Exploratory Data Analysis

- Distribution Analysis
- Route Type Comparison
- Delivery Time Analysis
- Distance Analysis
- Actual vs OSRM Analysis
- Correlation Analysis

### 6️⃣ Statistical Validation

- Actual vs OSRM comparisons
- Segment-level analysis
- Route-type comparisons

### 7️⃣ Business Insight Generation

- Logistics efficiency assessment
- Delivery performance evaluation
- Operational bottleneck identification
- Business recommendations

---

# 📈 Key Insights

## 🚚 Logistics Performance

- Actual delivery times consistently exceeded OSRM estimated times, indicating that routing estimates alone do not fully capture real-world operational delays.
- Average actual delivery time (~417 minutes) was nearly **2× higher** than the average OSRM estimated time (~214 minutes), highlighting significant operational inefficiencies.

### 📦 Route Operations

- **FTL (Full Truck Load)** accounted for approximately **69%** of all shipments and exhibited greater delivery time variability than Carting operations.
- Carting deliveries showed comparatively shorter and more consistent delivery durations.

### ⚙️ Data Engineering

- Shipment-level records were successfully aggregated into trip-level observations, creating an analytics-ready dataset suitable for forecasting and optimization.
- Datatype optimization reduced memory usage by approximately **40.6%**, improving computational efficiency.

### 📊 Data Quality

- Missing values were effectively handled using location-based imputations.
- No duplicate records were identified, indicating good data integrity before feature engineering.

---

# 🎯 Business Impact

This analysis enables Delhivery to:

- Improve route planning by identifying gaps between estimated and actual delivery performance.
- Build more reliable ETA prediction models using engineered trip-level features.
- Detect operational bottlenecks across transportation routes.
- Improve logistics monitoring using standardized business KPIs.
- Reduce manual preprocessing by creating an analytics-ready dataset.
- Support data-driven logistics planning instead of relying solely on routing engine estimates.

---

# 💡 Business Recommendations

### 🚚 Improve Route Planning

Continuously compare actual delivery performance against OSRM estimates to identify consistently underperforming routes.

### 🚛 Monitor Transportation Modes Separately

Analyze **FTL** and **Carting** operations independently, as both exhibit different delivery characteristics and operational behavior.

### 📊 Build Operational Dashboards

Develop dashboards to monitor delivery delays, ETA accuracy, and route efficiency in real time.

### 🤖 Leverage Engineered Features

Use the engineered trip-level dataset for ETA prediction, demand forecasting, and logistics optimization models.

### ⚙️ Strengthen Data Quality Pipelines

Automate feature engineering, missing value treatment, and validation to improve the scalability and reliability of the logistics analytics pipeline.

---

# 🧠 Skills Demonstrated

- Data Cleaning
- Data Validation
- Feature Engineering
- Data Aggregation
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Outlier Detection
- Missing Value Treatment
- Feature Encoding
- Feature Scaling
- Logistics Analytics
- Business Analytics
- Root Cause Analysis
- Data Storytelling
- Business Recommendation Framework

---

# 📂 Repository Structure

```text
delhivery-logistics-feature-engineering-analysis/
│
├── data/
│   └── README.md
│
├── notebooks/
│   └── delhivery_logistics_feature_engineering_analysis.ipynb
│
├── reports/
│   └── delhivery_analysis_report.pdf
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

# 🚀 Deliverables

- ✅ End-to-End Data Cleaning Pipeline
- ✅ Feature Engineering Workflow
- ✅ Exploratory Data Analysis
- ✅ Statistical Validation
- ✅ Logistics Performance Analysis
- ✅ Business Insights
- ✅ Business Recommendations
- ✅ Complete Jupyter Notebook
- ✅ Executive PDF Report

---

# ⭐ If you found this project useful, consider giving it a star!

It helps others discover the project and supports my work.

---

# 👩‍💻 Author

**Richa Jain**

**Aspiring Data Analyst | Business Analyst | Python | SQL | Statistics | Tableau**

Passionate about transforming raw business data into actionable insights through analytics, statistics, feature engineering, and data-driven decision making.
