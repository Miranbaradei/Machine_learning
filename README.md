## Overview
This repository contains Jupyter Notebooks focused on **healthcare data preprocessing, visualization, and exploratory analysis**. The notebooks demonstrate how to clean, transform, and analyze large datasets of clinical records, specialties, and revenue trends.

## Contents
### 1. `revenue.ipynb`
- **Data Cleaning & Preprocessing**
  - Standardizes categorical fields such as medical specialties.
  - Extracts temporal features (Year, Month) from service dates.
  - Validates missing values in key identifiers (`DoctorID`, `Staff_name`).
- **Visualizations**
  - Line plots showing revenue fluctuations over time.
  - PairGrid scatter plots to explore relationships between variables.
  - Specialty-based revenue trends.

### 2. `hours.ipynb` / `hours1.ipynb`
- **Data Structure**
  - Large dataset (~108k entries, 17 columns) covering staff schedules, specialties, and working hours.
- **Preprocessing**
  - Conversion of time fields (`ActualStartTime`, `ActualEndTime`) into `timedelta` objects.
  - Filtering and grouping records by specialty.
- **Visualizations**
  - Line charts showing **number of records per specialty over time**.
  - Specialty distribution analysis, including “Other” category filtering.

## Key Features
- **Data Cleaning:** Handling null values, standardizing text fields, and ensuring consistent formats.
- **Exploratory Analysis:** Pairwise scatter plots, time-series revenue trends, and specialty-based distributions.
- **Scalability:** Works with large datasets (up to ~100k rows).
- **Healthcare Context:** Focused on specialties, staff scheduling, and revenue metrics.

## Applications
- Revenue forecasting and trend analysis.
- Specialty workload distribution.
- Identifying anomalies in staff schedules and clinic records.
- Supporting healthcare management decisions with data-driven insights.
