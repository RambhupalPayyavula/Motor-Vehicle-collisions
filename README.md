# 🚗 NYC Motor Vehicle Collisions Analysis (1.8M+ Records)

This project analyzes police-reported motor vehicle collisions in New York City using **large-scale data processing, statistical analysis, and time series modeling** to identify high-risk areas, temporal trends, and predictive relationships.

---

## 📊 Problem Statement

Understanding traffic collisions is critical for improving public safety.

This project aims to:
- Identify **high-risk boroughs and accident patterns**  
- Analyze **trends in injuries and fatalities over time**  
- Build **statistical and predictive models** to understand and forecast crash-related outcomes  

---

## ⚙️ Tech Stack

**Language:** Python  
**Data Processing:** pandas, numpy  
**Visualization:** matplotlib, seaborn  
**Statistical Modeling:** statsmodels  
**Machine Learning:** scikit-learn (Linear Regression)  
**Time Series:** SARIMAX  

---

## 🧼 Data Pipeline & Engineering

- **Dataset Scale:** ~1.83 million records, 29 attributes  

### 🔹 Data Cleaning
- Dropped irrelevant columns (GPS coordinates, redundant contributing factors)  
- Handled missing borough values by assigning to `"NYC"`  
- Filtered dataset to include **full calendar years (2013–2021)**  

👉 Result: Clean, structured dataset optimized for analysis  

---

## 📈 Analytical Approach

### 🔹 1. Exploratory Data Analysis (EDA)

- Compared injuries and fatalities across:
  - Pedestrians  
  - Cyclists  
  - Motorists  

- Identified distribution patterns and category-level differences  

---

### 🔹 2. Hypothesis Testing

- Performed **T-tests** to compare injury rates across boroughs  
- Example:
  - Queens vs Manhattan safety comparison  

👉 Established statistical significance in regional risk differences  

---

### 🔹 3. Predictive Modeling

#### Linear Regression
- Modeled relationships between:
  - Total injuries vs total fatalities  
  - Motorist injuries vs total injuries  

👉 Identified correlation patterns in accident severity  

---

### 🔹 4. Time Series Forecasting

- Implemented **SARIMAX model** for forecasting injury trends  
- Used **train-test split** for validation  

👉 Predicted future injury patterns based on historical data  

---

## 🏆 Key Insights

- **Highest Risk Borough:** Brooklyn (followed by Queens)  
- **Peak Injury Year:** 2018  
- **Cyclist Injury Spike:** 2020  
- **Pedestrian Fatalities Peak:** 2013  

👉 Clear temporal and spatial patterns in traffic safety  

---

## 📊 Visual Insights

- Trend analysis of injuries and fatalities over time  
- Comparative borough-level visualizations  
- Category-based breakdown (pedestrians, cyclists, motorists)  

---

## 📂 Repository Structure

```bash
NYC-Motor-Vehicle-Collisions/
├── Final_Project.ipynb              # Data pipeline, EDA, modeling
├── Capstone_project_report.docx    # Detailed analysis report
├── Final_project_Presentation.pptx # Stakeholder summary
