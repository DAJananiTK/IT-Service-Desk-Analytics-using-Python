# 🛠️ IT Service Desk Ticket Analysis Using Python

A comprehensive Data Analytics project that analyzes IT Service Desk ticket data using Python to identify ticket trends, evaluate support performance, monitor SLA compliance, and generate actionable business insights for improving IT service management.

---

## 📌 Project Overview

This project analyzes IT Service Desk ticket data using Python in Google Colab. The dataset was cleaned, transformed, and analyzed using Exploratory Data Analysis (EDA), statistical analysis, and data visualization techniques.

The project focuses on understanding:

- Ticket distribution and monthly trends
- Resolution performance across priorities
- Support channels and ticket categories
- Agent workload distribution
- SLA breaches and escalations
- IT service desk performance

---

## 🎯 Objectives

- Analyze overall ticket distribution and monthly trends.
- Evaluate ticket resolution performance across priority levels.
- Identify common ticket categories, affected services, and support channels.
- Assess support agent workload distribution.
- Examine SLA breaches, escalations, and outages.
- Generate insights to improve IT service desk performance.

---

## 🗂️ Dataset

**Source:** Hugging Face – Mindweave Help Desk Tickets Dataset

Main datasets used:

- tickets.csv
- agents.csv
- categories.csv
- sla_breaches.csv

Dataset Size:

- 1,000 Records
- 15 Attributes

---

## 🛠️ Tools & Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## ⚙️ Data Preprocessing

The following preprocessing steps were performed:

- Data type verification
- Missing value analysis
- Duplicate checking
- Removal of unnecessary columns
- Dataset merging
- Feature engineering

### New Features Created

- Resolution Status
- SLA Status
- Month

---

## 📊 Exploratory Data Analysis (EDA)

Performed:

- Dataset inspection
- Statistical summary
- Missing value analysis
- Duplicate validation
- Data type verification

---

## 📈 Statistical Analysis

Calculated statistical measures for:

- Actual Resolution Hours
- SLA Breach Minutes

Measures:

- Mean
- Median
- Mode
- Variance
- Standard Deviation
- Skewness
- Kurtosis

---

## 📉 Data Visualizations

### Univariate Analysis

- Ticket Priority Distribution
- Ticket Category Distribution
- Affected Service Distribution
- Support Channel Distribution
- Resolution Status Distribution
- Monthly Ticket Trend

### Bivariate Analysis

- Ticket Priority vs Resolution Time
- Ticket Priority vs Resolution Status
- Actual Hours vs Breach Minutes
- Assigned Agent vs Ticket Count
- Affected Service vs Ticket Priority

### Multivariate Analysis

- Correlation Heatmap
- Support Team vs Ticket Priority
- Average Resolution Hours by Service and Priority (Heatmap)

---
## 📊 Key Visualizations

### 1. Monthly Trend of IT Support Tickets

![Monthly Trend](images/Monthly%20Trend.png)

---

### 2. Distribution of Tickets by Status

![Ticket Status](images/ticket%20status.png)

---

### 3. Support Channel vs Resolution Status

![Channel vs Status](images/channel%20vs%20status.png)

---

### 4. Actual Resolution Hours vs SLA Breach Minutes

![Actual vs Breach](images/actual%20vs%20breach.png)

---

### 5. Correlation Heatmap

![Correlation Heatmap](images/corr%20heatmap.png)

## 🔍 Key Findings

- January recorded the highest ticket volume.
- P3 and P4 were the most common ticket priorities.
- 899 tickets were successfully resolved.
- Laptop/Endpoint was the most frequent ticket category.
- Endpoint was the most affected IT service.
- Email was the most commonly used support channel.
- Tier-1 handled the highest workload.
- SLA breaches and escalations highlighted opportunities for operational improvement.

---

## 📌 Types of Analysis

- Descriptive Analysis
- Diagnostic Analysis
- Predictive Analysis
- Prescriptive Analysis

---

## 🚀 Future Enhancements

- Analyze larger datasets
- Apply Machine Learning models
- Build interactive dashboards
- Automate reporting workflows

---

## ✅ Conclusion

This project demonstrates how Python-based data analytics can improve IT service management by identifying ticket trends, monitoring support performance, evaluating SLA compliance, and providing insights for better operational decision-making.






