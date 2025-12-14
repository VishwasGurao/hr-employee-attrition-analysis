# HR Employee Attrition Analysis & Prediction

## 📌 Project Overview
Employee attrition is a major challenge for organizations, leading to
increased hiring costs, productivity loss, and team instability.
This project performs an **end-to-end HR analytics and machine learning
workflow** to analyze employee attrition and predict employees who are
at risk of leaving the organization.

The project combines **data analysis, business insights, and machine
learning** to support proactive HR decision-making.

---

## 🎯 Objectives
- Understand key factors contributing to employee attrition
- Perform exploratory data analysis (EDA) with business interpretation
- Build and evaluate machine learning models to predict attrition
- Align model evaluation with real HR business priorities
- Provide actionable insights for employee retention

---

## 🗂 Dataset
- **Source:** IBM HR Analytics Employee Attrition Dataset
- **Records:** 1,470 employees
- **Features:** Demographics, job role, compensation, satisfaction,
  work-life balance, experience
- **Target Variable:** `Attrition` (Yes / No)

---

## 🔍 Exploratory Data Analysis (EDA)
Key insights discovered during analysis:
- Overall attrition rate is approximately **16%**
- Higher attrition observed among **younger and mid-career employees**
- **Overtime** is one of the strongest drivers of attrition
- Employees with **lower income and lower job satisfaction** are more
  likely to leave
- Attrition risk varies significantly across **job roles**

EDA was supported with visualizations and business-focused interpretations.

---

## 🤖 Machine Learning Approach

### Models Implemented
- **Logistic Regression** – Interpretable baseline model
- **Random Forest Classifier** – Advanced non-linear model

### Key Techniques
- One-hot encoding for categorical variables
- Handling class imbalance using class weights
- Stratified train-test split
- Threshold tuning to prioritize recall for attrition cases
- Evaluation using **ROC–AUC**, precision, recall, and F1-score

### Model Performance
- Logistic Regression ROC–AUC ≈ **0.81**
- Random Forest provided improved robustness
- Threshold tuning improved identification of high-risk employees

---

## 📊 Feature Importance
Feature importance analysis identified the strongest predictors of
employee attrition:
- Overtime
- Monthly Income
- Job Satisfaction
- Years at Company
- Age
- Work-Life Balance

These results closely align with EDA findings, reinforcing model reliability.

---

## 🧠 Business Usage
This model can be used by HR teams as an **early warning system**:
1. Run the model periodically on employee data
2. Identify employees with high attrition risk
3. Take proactive actions such as:
   - Career discussions
   - Workload adjustment
   - Compensation review
   - Learning and development initiatives
4. Monitor attrition trends over time

---

## ⚠️ Limitations
- Based on historical employee data
- External factors such as market conditions and manager behavior
  are not included
- Predictions are probabilistic and should support, not replace,
  human decision-making

---

## 🛠 Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📁 Repository Contents
- `hr_attrition_analysis.ipynb` – Complete analysis and modeling notebook
- `hr_employee_attrition.csv` – Dataset used for analysis
- `README.md` – Project documentation

---

## 👤 Author
**Vishwash Balbhim Gurav**  
Aspiring Data Analyst / Data Scientist

---

## ⭐ Conclusion
This project demonstrates a complete, business-aligned data science
workflow for employee attrition analysis and prediction. By combining
data-driven insights with machine learning, the solution supports
proactive HR strategies to reduce attrition and improve workforce stability.
