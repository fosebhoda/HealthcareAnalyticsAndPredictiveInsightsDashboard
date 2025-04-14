# 🏥 Healthcare Analytics & Predictive Insights Dashboard

An end-to-end healthcare data analytics project using synthetic patient data to explore hospital trends, visualize medical insights, and predict test outcomes. This project combines SQL-based exploration, interactive Power BI dashboards, and Python-based machine learning modeling.

---

## 🔍 Project Overview

This project simulates a real-world healthcare data workflow. Starting from raw synthetic data, I cleaned and analyzed patient information using SQL, visualized insights through Power BI, and applied predictive modeling using Python to forecast medical test results.

The goal: uncover hidden patterns in billing, admissions, demographics, and care outcomes — then use that insight to make informed, data-driven predictions.

---

## 💻 Tools & Technologies

- **SQL** – Data exploration, joins, filtering, aggregations
- **Power BI** – Interactive dashboard creation and data storytelling
- **Python** *(Jupyter Notebook)* – Data preprocessing, correlation analysis, ML modeling
- **Pandas / Scikit-learn / Matplotlib / Seaborn** – Data analysis & modeling
- **Git & GitHub** – Version control and collaboration

---

## 🧼 Data Cleaning & Exploration

- Cleaned missing values and standardized columns
- Created derived features (e.g. age groups)
- Analyzed variable relationships via SQL (e.g. test results vs medications)
- Uncovered trends in patient demographics, hospital billing, and care types

---

## 📊 Dashboard Highlights

**📄 Page 1 – General Overview & Billing**  
_“Patient Demographics, Admissions, and Hospital Billing Trends”_
- Donut Chart: Gender distribution
- Line & Column Charts: Monthly admissions & medical conditions
- Funnel Charts: Top/Bottom hospitals by billing
- Bar Chart: Medication usage across hospitals

**📄 Page 2 – Medical Insights**  
_“Medical Conditions, Care Outcomes, and Admission Patterns”_
- Stacked Bars: Billing by admission type
- Bar Chart: Average length of stay by test results
- Stacked Columns: Test result distribution by condition
- Slicer: Filter by patient blood type

**📄 Page 3 – Predictive Modeling**  
_“Feature Importance and Model Evaluation for Test Result Prediction”_
- Random Forest feature importance plot
- Confusion matrix visualization

---

## 🔮 Predictive Modeling

Defined a multi-class classification task to predict a patient's **Test Result** (`Normal`, `Abnormal`, or `Inconclusive`) based on:
- Age, Gender, Medical Condition
- Admission Type
- Medication Prescribed

Model:
- Used **Random Forest Classifier** **Logistic Regression** **Decision Tree**
- Evaluated with a confusion matrix and feature importance based on **Random Forest Classifier**

---

## 🚀 **Next Steps & Key Takeaways**

This project not only sharpened my skills in SQL, Power BI, and Python, but also deepened my understanding of how healthcare data can drive actionable insights. The experience in predictive modeling, data visualization, and feature engineering gave me valuable exposure to real-world challenges in the healthcare domain.

I’m excited to continue building on these skills and explore more complex datasets to make impactful contributions to the healthcare industry through data.

Feel free to reach out if you'd like to discuss healthcare analytics, predictive modeling, or collaborate on similar projects!

---

## 📂 Data Source

The dataset used in this project was obtained from **Kaggle**:  
[🔗 Healthcare Dataset](https://www.kaggle.com/datasets/prasad22/healthcare-dataset)

This synthetic dataset contains information on patient demographics, medical conditions, diagnostic test results, hospital admissions, medications, and billing details.

---

