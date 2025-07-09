# 📊 Data Analysis & Machine Learning Projects

This repository contains 8 different mini-projects covering exploratory data analysis (EDA), data visualization, clustering, regression, and prediction tasks using real-world datasets across domains like sales, student performance, customer segmentation, COVID-19, e-commerce, Netflix usage, traffic, and surveys.

---

## 📁 Project Overview

### 🔢 Problem 1: Sales Revenue Forecasting
- **Dataset**: Daily sales and revenue
- **Goal**: Predict future revenue using Linear Regression
- **Key Steps**:
  - Time series aggregation
  - Feature engineering (`days_since_start`)
  - Model training and evaluation (`R²`, `MSE`)
  - Revenue forecast for the next 7 days
- **Issue**: Linear regression model is not suitable due to poor fit (`R² = -0.44`)

---

### 🎓 Problem 2: Student Performance Analysis
- **Dataset**: Student marks, attendance, and logins
- **Goal**: Analyze impact of attendance and logins on performance
- **Key Insights**:
  - Strong positive correlation between marks, attendance, and logins
  - Identified top and struggling students
  - Visualized performance with scatterplots and heatmaps

---

### 🧑‍💼 Problem 3: Customer Segmentation (KMeans Clustering)
- **Dataset**: Customer demographics and behavior
- **Goal**: Segment customers into 4 clusters
- **Techniques**:
  - Feature scaling (`StandardScaler`)
  - Clustering with `KMeans`
  - 2D and 3D visualizations
  - Cluster-wise summary statistics

---

### 🦠 Problem 4: COVID-19 Cumulative Case Analysis
- **Dataset**: Fictional cumulative COVID case data
- **Goal**: Visualize case trends over time per country
- **Output**:
  - Line chart of cumulative confirmed cases across multiple countries

---

### 🛍️ Problem 5: E-commerce Sales Analysis
- **Dataset**: E-commerce transactions
- **Goals**:
  - Identify top-selling products
  - Analyze sales by hour
  - Visualize user retention
- **Charts**: Bar chart, line plot, pie chart

---

### 📺 Problem 6: Netflix User Behavior Analytics
- **Dataset**: Netflix watch logs
- **Goals**:
  - Total watch time per user
  - Genre preferences and ratings
  - Binge-watching detection
- **Charts**: Bar chart, pie chart, scatter plots, count plots

---

### 🚦 Problem 7: Traffic Volume Analysis & Prediction
- **Dataset**: Hourly traffic count per location
- **Goals**:
  - Identify peak traffic hours
  - Predict vehicle count using Linear Regression
- **Key Insight**: Evening hours show higher vehicle counts

---

### 📝 Problem 8: Survey Analysis
- **Dataset**: Survey responses on e-commerce experience
- **Goals**:
  - Analyze satisfaction ratings
  - Platform preference
  - Mobile app usage by age group
  - Satisfaction vs platform heatmap
- **Charts**: Count plots, heatmaps

---

## 🛠 Libraries Used

- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `sklearn`: `LinearRegression`, `KMeans`, `StandardScaler`, `train_test_split`, `metrics`
- `mpl_toolkits.mplot3d` (for 3D plotting)

---

## 📦 How to Run

1. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
