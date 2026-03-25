# Predictive Maintenance Analytics using SQL, BigQuery and Tableau

## Project Overview
This project analyzes aircraft engine sensor data to predict equipment failure and estimate Remaining Useful Life (RUL). SQL was used to build analytical datasets in Google BigQuery, and Tableau was used to create dashboards for engine lifecycle, sensor degradation, and failure distribution analysis.

The project simulates a real-world predictive maintenance analytics workflow used in manufacturing, aviation, and industrial equipment monitoring.

---

## Objectives
- Calculate Remaining Useful Life (RUL) using SQL window functions
- Analyze engine lifecycle and failure distribution
- Identify sensor degradation patterns
- Build predictive maintenance dashboard in Tableau
- Demonstrate SQL data modeling and analytics workflow

---

## Tools Used
- SQL (Google BigQuery)
- Tableau
- Excel
- GitHub

---

## Dataset
NASA Turbofan Engine Degradation Dataset

This dataset contains engine sensor readings across multiple operating cycles until engine failure. It is commonly used for predictive maintenance and Remaining Useful Life modeling.

---

## Project Workflow
1. Data cleaning and schema creation
2. Remaining Useful Life (RUL) calculation using window functions
3. Engine lifecycle and failure distribution analysis
4. Sensor degradation trend analysis
5. Predictive maintenance analytics dataset creation
6. Dashboard development in Tableau

---

## Data Model
The project creates multiple analytical tables:

- **engine_cleaned** → Cleaned dataset with proper column names
- **engine_rul** → Dataset with Remaining Useful Life (RUL)
- **engine_summary** → Engine lifecycle summary
- **sensor_degradation** → Sensor trends vs Remaining Life
- **failure_distribution** → Engine failure distribution
- **engines_near_failure** → Engines close to failure

---

## Key Insights
- Most engines fail between **120–180 cycles**
- Sensor degradation patterns appear as engines approach failure
- Remaining Useful Life can be used for predictive maintenance scheduling
- Engine lifecycle distribution helps in maintenance planning
- Sensor trend analysis helps identify degradation indicators

---

## Repository Structure
predictive-maintenance-analytics
│
├── data
├── sql
│ ├── 01_create_clean_table.sql
│ ├── 02_create_rul_table.sql
│ ├── 03_engine_summary.sql
│ ├── 04_sensor_degradation.sql
│ ├── 05_failure_distribution.sql
│ └── 06_engines_near_failure.sql
│
├── tableau
├── images
│ └── dashboard.png
│
└── README.md

---

## Dashboard Preview
![Dashboard](https://github.com/Uelinje/Predictive-Maintenance-Analytics-using-SQL-BigQuery-and-Tableau/blob/main/predictive-maintenance-analytics/tableau/images/dashboard.png)

---

## Conclusion
This project demonstrates how SQL can be used for industrial analytics, predictive maintenance, and equipment lifecycle analysis. The workflow includes data cleaning, feature engineering, lifecycle analytics, and dashboard visualization.

This type of analysis is commonly used in manufacturing analytics, operations analytics, and industrial data science.
