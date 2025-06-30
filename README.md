# Internship-Project-

# HR Analytics – Predict Employee Attrition 🚨

This project focuses on analyzing employee data to identify key reasons for attrition (resignations) and predict future attrition using data science techniques. The insights help HR teams take proactive steps to improve employee retention.

---

## 📌 Objective

Use analytics to understand the main causes of employee resignation and build a predictive model to forecast future attrition.

---

## 🧰 Tools & Technologies Used

- **Python** (Pandas, Seaborn, Scikit-learn, SHAP)
- **Power BI** (Dashboard and Visualization)
- **Jupyter Notebook / Google Colab**
- **Dataset**: HR Employee Attrition Dataset (1470 rows × 31 columns)

---

## 🧪 Steps Involved

### 1. Data Cleaning & Preprocessing
- Removed irrelevant columns (`EmployeeCount`, `EmployeeNumber`, etc.)
- Converted categorical variables to numerical
- Mapped target column `Attrition`: Yes = 1, No = 0

### 2. Exploratory Data Analysis (EDA)
Visualized relationships between:
- Attrition and Job Satisfaction
- Attrition and Monthly Income
- Attrition and OverTime
- Attrition and Years Since Last Promotion
- Attrition and Department/Gender

### 3. Model Building
- Used **Logistic Regression** for classification
- Achieved accuracy of **87.75%**
- Confusion Matrix used for performance evaluation

### 4. Explainability with SHAP
- Identified top factors influencing attrition using SHAP values
- Key features: `OverTime`, `MonthlyIncome`, `JobSatisfaction`, `YearsAtCompany`

### 5. Power BI Dashboard
- 3 Bar Charts: Attrition by Department, Gender, Job Satisfaction
- 2 Pie/Donut Charts: Gender Distribution, Attrition Rate
- 1 Line Chart: Average Monthly Income by Age
- 3 Slicers: Gender, Department, Job Role

---

## 📈 Model Evaluation

- **Accuracy**: 87.75%
- **Confusion Matrix**:
```

\[\[252   3]
\[ 33   6]]

```

---

## 📊 Power BI Dashboard Preview

> The dashboard provides HR teams with a comprehensive view of attrition trends across departments, gender, job satisfaction levels, and more.

---

## ✅ Conclusion

- Employees working overtime, earning less, or dissatisfied with their jobs are more likely to leave.
- Regular promotions and career growth opportunities can help reduce attrition.
- The dashboard and model can guide HR strategy and decision-making.

---

## 📁 Files Included

- `HR-Attrition-EDA-and-Model.ipynb` → Python notebook
- `Cleaned_HR_Attrition.csv` → Cleaned dataset
- `Attrition_Dashboard.pbix` → Power BI dashboard
- `Project_Report.pdf` → Final 2-page report

---

## 📬 Suggestions to HR (From Analysis)

- Monitor OverTime employees more closely
- Improve satisfaction through engagement initiatives
- Plan career growth paths with timely promotions
- Address pay disparities in high-risk departments

---
