# Citi Bike Big Data Analytics

## Project Overview

This project was developed as part of the Big Data & NoSQL course. The objective was to build an end-to-end big data analytics pipeline using Apache Spark on Citi Bike trip data, covering data preprocessing, feature engineering, analytical querying, machine learning, and business intelligence visualization.

---

## Technologies Used

- Apache Spark
- PySpark
- Spark SQL
- Spark MLlib
- Python
- Jupyter Notebook
- Power BI

---

## Project Workflow

1. Data Loading
2. Data Exploration
3. Data Cleaning & Preprocessing
4. Feature Engineering
5. Noise Detection
6. Spark SQL Analytics
7. Machine Learning Modeling
8. Power BI Visualization

---

## Feature Engineering

The following features were created from the raw trip data:

- Rider Age
- Trip Duration
- Trip Distance (Haversine Formula)
- Average Speed
- Period of Day Classification
- Seasonal Categorization

---

## Analytical Insights

The project explored several business and operational questions, including:

- Most popular start and destination stations
- Peak riding hours
- Seasonal demand patterns
- Weekday vs weekend behavior
- User demographic analysis
- Bike utilization monitoring
- Station mobility flow analysis

---

## Machine Learning

A classification pipeline was implemented using Spark MLlib.

### Models Evaluated

- Logistic Regression
- Decision Tree
- Random Forest

### Features Used

- Age
- Trip Duration
- Trip Distance
- Average Speed
- User Type
- Month
- Period of Day

Random Forest achieved the best overall performance due to its ability to capture complex relationships and handle noisy real-world transportation data.

---

## Power BI Dashboard

As a bonus component, Power BI dashboards were developed to visualize key insights extracted from the Citi Bike dataset.

### Dashboard 1 – System Performance Overview

- Total Trips Analysis
- Average Trip Duration
- Average Riding Speed
- Average Distance Traveled
- User Type Distribution
- Gender Distribution
- Riding Activity by Period of Day


---

### Dashboard 2 – Temporal Demand & Riding Pattern Analysis

- Peak Demand Hour
- Seasonal Demand Trends
- Hourly Demand Distribution
- Weekday vs Weekend Comparison
- Seasonal User-Type Analysis


---

### Dashboard 3 – Station Popularity & Mobility Flow Analysis

- Most Popular Start Station
- Most Popular Destination Station
- Top 10 Start Stations
- Top 10 Destination Stations
- Mobility Flow Insights

---

## Key Learning Outcomes

- Distributed data processing using Apache Spark
- Data cleaning and feature engineering at scale
- Spark SQL analytical querying
- Window Functions and UDF implementation
- Machine Learning using Spark MLlib
- Business Intelligence visualization with Power BI

---

## Authors

Big Data & NoSQL Course Project Team
