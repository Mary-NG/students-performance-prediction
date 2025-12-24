# 📊 Student Performance Analysis (Microsoft Excel)

## 📌 Project Overview
This project investigates factors influencing students’ academic performance using **Microsoft Excel**. The analysis focuses on **attendance percentage**, **study hours**, **education level**, and **study methods**, applying **pivot tables**, **data visualizations**, and **regression analysis** to identify patterns and statistically supported relationships.

All analyses were conducted using Excel’s built-in analytical tools for academic purposes.

---

## 🎯 Objectives
- To examine the relationship between **attendance percentage** and final grades
- To analyze how **study hours** affect student performance
- To compare academic performance across **subjects**
- To evaluate whether **education level** predicts academic performance
- To assess the impact of different **study methods** on student outcomes

---

## 📂 Dataset Description
The dataset contains records for **25,000 students**, including:
- Attendance percentage
- Study hours
- Subject (Mathematics, English, Science)
- Education level
- Study methods
- Final grades / performance scores

The dataset is used strictly for **educational and analytical purposes**.

---

## 🔍 Data Analysis Methods

### 1️⃣ Pivot Table Analysis

Pivot tables were used extensively to summarize and compare student performance.

#### 🔹 Attendance Percentage and Performance
- Average final grades were calculated for different attendance levels
- Results showed that students with higher attendance consistently achieved higher mean grades

#### 🔹 Study Hours and Performance
- Study hours were grouped into categories (low, medium, high)
- Pivot tables showed a general increase in average performance as study hours increased

#### 🔹 Subject-wise Performance Comparison
- Average grades were compared across Mathematics, English, and Science
- Differences in performance were observed across subjects, indicating subject-specific trends

---

### 2️⃣ Data Visualization
Charts generated from pivot tables included:
- Bar charts showing average grades by attendance category
- Charts comparing performance across study-hour groups
- Subject-wise performance comparison charts

These visualizations supported clear interpretation of trends and group differences.

---

## 📈 Regression Analysis

### 🔹 Regression 1: Attendance Percentage and Final Grades
A **simple linear regression** was conducted using Excel’s **Data Analysis ToolPak**.

- **Dependent variable:** Final grade  
- **Independent variable:** Attendance percentage  
- **Observations:** 25,000  

**Results:**
- R Square = 0.0857 (≈ 8.6%)
- Regression coefficient (β) = 0.386
- p-value < 0.001
- F-statistic = 2343.41

**Interpretation:**
There is a positive and statistically significant relationship between attendance percentage and academic performance. A 1% increase in attendance is associated with an average increase of approximately 0.39 marks in final grades. Attendance explains about 8.6% of the variation in student performance, making it the strongest predictor examined in this project.

---

### 🔹 Regression 2: Education Level and Academic Performance
A **multiple linear regression** examined whether education level predicts performance.

- **Independent variables:** Post-graduate, graduate, high school, diploma, PhD  
- **Observations:** 25,000  

**Results:**
- R Square = 0.00063 (0.063%)
- Adjusted R Square = 0.00043
- Significance F = 0.0075

**Interpretation:**
Although the model is statistically significant, education level explains less than 0.1% of the variation in academic performance. None of the education categories are statistically significant predictors at the 5% level. This indicates that education level does not have a meaningful practical impact on performance in this dataset.

---

### 🔹 Regression 3: Study Methods and Academic Performance
A **multiple linear regression** was conducted to assess the impact of different study methods.

- **Independent variables:**  
  Extra activities, note-taking, group study, coaching, mixed methods, online videos  
- **Observations:** 25,000  

**Results:**
- R Square = 0.00070 (0.07%)
- Adjusted R Square = 0.00046
- Significance F = 0.0078

**Interpretation:**
The model explains less than 0.1% of the variation in academic performance, indicating extremely weak explanatory power. Among the study methods, only group study is statistically significant (p < 0.05) and shows a small negative association with performance. All other study methods are not statistically significant predictors.

Overall, study methods do not meaningfully predict academic performance in this dataset.

---

## 📊 Summary of Key Findings
- Attendance percentage is a **significant and meaningful predictor** of academic performance
- Study hours show positive trends in pivot table analysis
- Education level and study methods have **statistically significant but practically negligible effects**
- Large sample size contributes to statistical significance despite very low explanatory power in some models
- Pivot tables and regression results together highlight attendance as the most influential factor

---

## 🛠️ Tools Used
- **Microsoft Excel**
  - Pivot Tables
  - Charts and Graphs
  - Data Analysis ToolPak (Regression)

---

## 📁 Repository Structure
```text
├── data/
│   └── student_performance_dataset.xlsx
├── pivot_tables/
│   └── summary_tables.xlsx
├── regression/
│   └── regression_outputs.xlsx
├── charts/
│   └── excel_charts.png
└── README.md
