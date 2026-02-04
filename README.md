# Big-Data-Oriented-Exploratory-Data-Analysis-on-Airbnb-Listings

# 📌 Project Overview
This project focuses on performing advanced exploratory data analysis (EDA) on a large, real-world Airbnb listings dataset. The goal is to analyze the dataset from a big data perspective by examining volume, variety, data quality, schema behavior, temporal trends, and statistical characteristics.
The analysis is implemented using efficient Python-based data science techniques suitable for large-scale datasets.

---
# 📂 Dataset Information
- **Source:** Kaggle – Airbnb Listings Dataset  
- **File Used:** airbnb-listings.csv  
- **Domain:** E-commerce / Marketplace / Geo-temporal Data  
The dataset contains information about Airbnb listings such as pricing, availability, room types, locations, reviews, and host details.

---
## 🛠 Tools & Technologies
- Python  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- Jupyter Notebook  

---

## 🔍 Tasks Performed

### 1. Data Volume Analysis
- Measured number of records and attributes
- Estimated memory usage
- Analyzed data growth over time using timestamps

### 2. Data Variety Analysis
- Identified structured and semi-structured data
- Examined text-based and complex attributes

### 3. Data Quality Assessment
- Detected duplicate records
- Identified inconsistent formats and invalid values
- Performed basic data cleaning

### 4. Schema & Schema Drift Analysis
- Inspected dataset schema
- Analyzed missing or changing fields over time

### 5. Missing Value Analysis
- Computed missing value counts and percentages
- Identified attributes with high missingness

### 6. Statistical Summary & Distribution Analysis
- Generated summary statistics
- Analyzed numerical and categorical distributions

### 7. Outlier Detection
- Detected outliers using the IQR method
- Visualized extreme values using box plots

### 8. Skewness & Class Imbalance Analysis
- Identified skewed numerical features
- Analyzed imbalance in categorical attributes

### 9. Temporal & Trend Analysis
- Performed monthly time-based aggregation
- Identified trends and seasonal patterns

### 10. Sampling & Approximate EDA
- Applied random sampling for efficiency
- Compared sampled statistics with full dataset metrics

---

## 📊 Visualizations Included
- Price distribution and log-transformed distribution
- Room type vs price comparison
- Correlation heatmap
- Temporal trend plots
- Neighborhood-level distribution analysis

---

## 🎯 Key Learnings
- Practical application of big data EDA concepts
- Handling large real-world datasets efficiently
- Understanding data behavior before modeling
- Importance of data quality and schema analysis

---

## 🚀 Future Enhancements
- Feature engineering for machine learning
- Price prediction using regression models
- Recommendation system based on location and price
- Migration to PySpark for large-scale processing
