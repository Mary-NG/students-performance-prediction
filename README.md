# 📊 Student Performance Analysis Using Microsoft Excel



<img width="740" height="740" alt="Image" src="https://github.com/user-attachments/assets/46941aca-f426-44cf-91ec-41f20a71f78d" />




## 1. Introduction
Academic performance is influenced by a combination of behavioural, academic, and socio-economic factors. Understanding how these factors relate to student outcomes can support better educational planning and decision-making.

This project uses **Microsoft Excel** to analyze student performance data in order to answer specific **business (analytical) questions** related to attendance, study habits, background characteristics, and learning strategies. The analysis combines **pivot tables**, **data visualization**, and **regression analysis** to provide both descriptive and inferential insights.

---

## 2. Business / Research Questions
This analysis is guided by the following business questions:

1. How does overall student performance differ by **school type**, **gender**, and **internet access**?  
2. How does students’ average performance change across different levels of **study hours**?  
3. What is the relationship between **attendance percentage** and students’ overall score?  
4. How does **parental education level** relate to students’ academic performance?  
5. How do **extracurricular activities and study methods** affect students’ academic performance?

Each question is addressed using appropriate Excel-based analytical techniques.

---

## 3. Dataset Description
The dataset consists of **25,000 student observations** and includes the following variables:

- Overall score / final grade  
- Attendance percentage  
- Study hours  
- School type  
- Gender  
- Internet access  
- Parental education level  
- Study methods and extracurricular activities  
- Subject (Mathematics, English, Science)

The dataset is used strictly for **educational and analytical purposes**.

---

## 4. Data Preparation
Prior to analysis:
- Data was reviewed for consistency and completeness
- Categorical variables were grouped appropriately
- Study hours were categorized (low, medium, high) for pivot table analysis
- All analyses were conducted using **Microsoft Excel**

---

## 5. Descriptive Analysis Using Pivot Tables

### 5.1 Business Question 1  
**How does overall student performance differ by school type, gender, and internet access?**

**Method Used:** Pivot tables and charts  

Pivot tables were created to calculate **average overall scores** across:
- Different school types
- Gender categories
- Internet access (yes/no)

**Findings:**
- Differences in average performance were observed across school types
- Gender-based performance differences were identified
- Students with internet access generally showed higher average performance

These results highlight how access to resources and demographic characteristics are associated with performance differences.

---

### 5.2 Business Question 2  
**How does students’ average performance change across different levels of study hours?**

**Method Used:** Pivot tables and charts  

Study hours were grouped into **low, medium, and high** categories.

**Findings:**
- Average performance increased as study hours increased
- Students in the high study-hour group achieved the highest mean scores
- The relationship showed a positive trend, though not perfectly linear

This suggests that increased study time is associated with improved academic outcomes.

---

### 5.3 Subject-wise Performance Comparison
Pivot tables were also used to compare average performance across subjects (Mathematics, English, Science).

**Findings:**
- Mean scores differed across subjects
- Subject characteristics contribute to variation in student performance
- These differences help explain variation not captured by single-variable models

---

## 6. Data Visualization
Charts were generated directly from pivot tables to support interpretation:
- Bar charts showing performance by school type, gender, and internet access
- Charts comparing performance across study-hour categories
- Subject-wise performance comparison charts

Visualizations enhanced clarity and supported evidence-based interpretation.

---

## 7. Regression Analysis

### 7.1 Business Question 3  
**What is the relationship between attendance percentage and students’ overall score?**

**Method Used:** Simple linear regression (Excel Data Analysis ToolPak)

- **Dependent variable:** Overall score  
- **Independent variable:** Attendance percentage  
- **Observations:** 25,000  

**Key Results:**
- R Square = 0.0857 (≈ 8.6%)
- Regression coefficient (β) = 0.386
- p-value < 0.001
- F-statistic = 2343.41

**Interpretation:**
There is a positive and statistically significant relationship between attendance and academic performance. A 1% increase in attendance is associated with an average increase of approximately 0.39 marks in overall score. Attendance explains about 8.6% of the variation in performance, making it the most practically meaningful predictor in this analysis.

---

### 7.2 Business Question 4  
**How does parental education level relate to students’ academic performance?**

**Method Used:** Multiple linear regression

- **Independent variables:**  
  High school, diploma, graduate, post-graduate, PhD  
- **Observations:** 25,000  

**Key Results:**
- R Square = 0.00063 (0.063%)
- Adjusted R Square = 0.00043
- Significance F = 0.0075

**Interpretation:**
Although the model is statistically significant, parental education level explains less than 0.1% of the variation in academic performance. None of the education categories are statistically significant predictors at the 5% level. This indicates that parental education level has negligible practical impact on student performance in this dataset.

---

### 7.3 Business Question 5  
**How do extracurricular activities and study methods affect students’ academic performance?**

**Method Used:** Multiple linear regression

- **Independent variables:**  
  Extra activities, note-taking, group study, coaching, mixed methods, online videos  
- **Observations:** 25,000  

**Key Results:**
- R Square = 0.00070 (0.07%)
- Adjusted R Square = 0.00046
- Significance F = 0.0078

**Interpretation:**
The regression model explains less than 0.1% of the variation in academic performance. Only group study is statistically significant at the 5% level and shows a small negative association with performance. All other study methods and extracurricular activities are not statistically significant predictors.

Overall, study methods and extracurricular activities do not meaningfully explain academic performance in this dataset.

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
i am open to collaborate on data analysis,visualization related projects, and statical analysis. you can reach me via email(ngoouzor@gamil.com)

