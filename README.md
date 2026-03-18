# UPSC Data Analytics & Visualization Project

## 📌 Project Overview
This project is a comprehensive data analytics study of the UPSC (Union Public Service Commission) examination trends. It demonstrates a full data pipeline—from raw data management using **SQL**, predictive modeling with **Python**, to high-impact storytelling via **Power BI**. 

The goal is to provide actionable insights into candidate demographics, success rates, and performance trends over multiple years.

---

## 🛠️ Technical Stack
* **Database Management**: SQL (SSMS / MySQL) – Used for data cleaning, transformation, and creating optimized views for reporting.
* **Data Science**: Python (Pandas, Scikit-learn, Matplotlib) – Applied for Exploratory Data Analysis (EDA) and Regression modeling to forecast trends.
* **Data Visualization**: Power BI Desktop – Designed a multi-page interactive dashboard for deep-dive analysis.

---

## 📊 Key Features & Dashboards
The Power BI report (`UPSC VISUALISATION.pbix`) consists of several specialized pages designed to provide a 360-degree view of the data:

* **Multi-Page Navigation**: Structured layout separating high-level summaries from granular demographic details.
* **Advanced Visuals**:
    * **Radar Charts**: Integrated to compare multi-dimensional candidate profiles and performance across different examination categories.
    * **Trend Analysis**: Time-series charts visualizing growth in applicant numbers and success ratios.
* **Predictive Insights**: Using Python-based regression models to understand the key drivers of examination success.

---

## 📂 Project Structure
```text
├── data/               # Raw and cleaned CSV/Excel datasets
├── sql_scripts/        # SQL files containing view definitions and EDA queries
├── notebooks/          # Jupyter notebooks for Python modeling and Regression
├── dashboard/          # UPSC VISUALISATION.pbix and report screenshots
└── README.md           # Project documentation
