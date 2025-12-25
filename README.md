# 📊 Student Performance Analysis Using Microsoft Excel


<img width="740" height="740" alt="Image" src="https://github.com/user-attachments/assets/46941aca-f426-44cf-91ec-41f20a71f78d" />


## 📌 Project Overview
This project analyzes student academic performance using **Microsoft Excel** to identify key factors influencing overall scores. The analysis combines **pivot tables** and **regression techniques** to answer business and academic questions related to attendance, study habits, parental education, and access to resources.

All analyses were conducted on a dataset containing **25,000 student records**.

---

## 🎯 Business / Research Questions

1. How does overall student performance differ by school type, gender, and internet access?
2. How does students’ average performance change across different levels of study hours?
3. What is the relationship between attendance percentage and students’ overall score?
4. How does parental education level relate to students’ academic performance?
5. How do extracurricular activities and study methods affect students’ academic performance?

---

## 🛠 Tools Used
- Microsoft Excel  
- Excel Pivot Tables  
- Excel Data Analysis ToolPak (Regression)

---

## 📊 Analysis & Results

---

## 1️⃣ Performance by School Type, Gender, and Internet Access (Pivot Tables)

Pivot tables were used to compare average student scores across demographic and access-related categories.

**Key Findings:**
- Student performance varies across different school types.
- Small but noticeable differences exist between genders.
- Students with internet access consistently perform better on average than those without access.

*Method used:* Pivot Tables

---

## 2️⃣ Study Hours and Academic Performance (Pivot Tables)

Students were grouped into study-hour categories (Low, Medium, High) using Excel bins.

| Study Hours Category | Average Performance |
|---------------------|--------------------|
| Low | Lower mean score |
| Medium | Moderate mean score |
| High | Highest mean score |

**Interpretation:**  
Average academic performance increases as study hours increase, indicating a positive descriptive relationship between time spent studying and performance.

*Method used:* Pivot Tables

---

## 3️⃣ Regression Analysis: Attendance Percentage and Overall Score

A simple linear regression was conducted to examine the effect of attendance on students’ overall scores.

### Regression Statistics

| Metric | Value |
|------|------|
| Observations | 25,000 |
| Multiple R | 0.293 |
| R Square | 0.0857 (8.6%) |
| Adjusted R Square | 0.0857 |
| Standard Error | 18.10 |
| F-statistic | 2343.41 |
| Significance (p-value) | < 0.001 |

### Coefficients

| Variable | Coefficient (β) | Std. Error | t-stat | p-value |
|-------|---------------|-----------|-------|--------|
| Intercept | 35.05 | 0.61 | 57.56 | < 0.001 |
| Attendance Percentage | 0.386 | 0.008 | 48.41 | < 0.001 |

**Interpretation:**  
Attendance percentage has a positive and statistically significant relationship with overall student performance. A 1% increase in attendance is associated with an average increase of approximately 0.39 marks. Attendance explains about 8.6% of the variation in performance, indicating it is an important but not exclusive predictor.

*Method used:* Simple Linear Regression

---

## 4️⃣ Parental Education Level and Academic Performance

A multiple regression analysis was used to examine whether parental education level predicts students’ academic performance.

### Regression Statistics

| Metric | Value |
|------|------|
| Observations | 25,000 |
| Multiple R | 0.025 |
| R Square | 0.00063 (0.063%) |
| Adjusted R Square | 0.00043 |
| Standard Error | 18.93 |
| F-statistic | 3.16 |
| Significance (p-value) | 0.0075 |

### Coefficients

| Education Level | Coefficient | Std. Error | t-stat | p-value |
|---------------|------------|-----------|-------|--------|
| Intercept | 63.91 | 0.30 | 215.64 | < 0.001 |
| Post-graduate | 0.66 | 0.42 | 1.58 | 0.115 |
| Graduate | 0.05 | 0.42 | 0.12 | 0.905 |
| High school | −0.52 | 0.42 | −1.25 | 0.211 |
| Diploma | 0.74 | 0.41 | 1.80 | 0.072 |
| PhD | −0.37 | 0.42 | −0.88 | 0.379 |

**Interpretation:**  
Parental education level explains less than 0.1% of the variation in student performance. None of the education categories show a statistically significant effect, indicating very weak predictive power.

*Method used:* Multiple Linear Regression

---

## 5️⃣ Extracurricular Activities & Study Methods

A multiple regression model was used to evaluate the impact of extracurricular activities and different study methods on academic performance.

### Regression Statistics

| Metric | Value |
|------|------|
| Observations | 25,000 |
| Multiple R | 0.026 |
| R Square | 0.00070 (0.07%) |
| Adjusted R Square | 0.00046 |
| Standard Error | 18.93 |
| F-statistic | 2.91 |
| Significance (p-value) | 0.0078 |

### Coefficients

| Study Method | Coefficient | Std. Error | t-stat | p-value |
|------------|------------|-----------|-------|--------|
| Intercept | 64.10 | 0.31 | 204.01 | < 0.001 |
| Extra activities | 0.29 | 0.24 | 1.20 | 0.232 |
| Notes | −0.34 | 0.41 | −0.83 | 0.405 |
| Group study | −0.99 | 0.41 | −2.38 | 0.017 |
| Coaching | 0.13 | 0.42 | 0.31 | 0.755 |
| Mixed methods | −0.63 | 0.41 | −1.53 | 0.125 |
| Online videos | 0.45 | 0.41 | 1.08 | 0.279 |

**Interpretation:**  
Only group study shows a statistically significant effect, with a small negative association. Overall, extracurricular activities and study methods explain very little variation in academic performance.

*Method used:* Multiple Linear Regression

---

## 📁 Repository Contents
- Excel files containing pivot tables
- Excel regression outputs
- Final README documentation

---
## 8. Comparison of Findings Across Business Questions
- Attendance percentage shows both **statistical significance and practical relevance**
- Study hours show positive trends in descriptive analysis
- School type, gender, and internet access reveal meaningful group differences
- Parental education level and study methods show **statistical but not practical significance**
- Large sample size contributes to statistically significant results despite very low R² values in some models

---

## 9. Key Insights for Decision-Making
- Improving attendance may yield measurable improvements in student performance
- Increased study time is associated with higher average scores
- Access to resources such as internet connectivity is linked to better outcomes
- Background characteristics alone are weak predictors of performance

---

## 10. Tools Used
- **Microsoft Excel**
  - Pivot Tables
  - Charts and Graphs
  - Data Analysis ToolPak (Regression)

---

## ✅ Conclusion
This project demonstrates how Excel-based analytical tools can be used to explore academic performance data. While attendance shows a meaningful relationship with student performance, most other factors examined have limited explanatory power, highlighting the multifaceted nature of academic success.

## 11. Repository Structure
```text
├── data/
│   └── student_performance_dataset.xlsx
├── pivot_tables/
│   └── summary_tables.xlsx
├── regression/
│   └── regression_outputs.xlsx
├── charts/
│   └── excel_visualizations.png
└── README.md

These steps will help replicate the analysis and verify the findings

I am open to collaborate on data analysis,visualization related projects, and statical analysis. you can reach me via email:{ngoouzor@gmail.com}

