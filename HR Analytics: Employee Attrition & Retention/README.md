# HR Attrition & Retention – Risk Analytics Dashboard

## 📌 Project Overview

Employee attrition is a major challenge for organizations due to increased hiring costs, productivity loss, and knowledge drain.
This project focuses on **predicting employee attrition risk using Machine Learning** and translating the insights into a **one-page Power BI dashboard** for data-driven HR decision-making.

The system identifies **high-risk employees**, highlights **department-level exposure**, and estimates the **financial impact of potential attrition**.

---

## 🎯 Objectives

* Predict the probability of employee attrition using Machine Learning
* Identify key drivers contributing to employee turnover
* Create employee-level **Retention Risk Scores**
* Visualize insights through an **interactive one-page Power BI dashboard**
* Enable proactive retention strategies for HR teams

---

## 🛠️ Tech Stack

* **Python**: Pandas, NumPy, Scikit-learn
* **Machine Learning**: Random Forest Classifier
* **Data Visualization**: Power BI
* **Database / Querying**: SQL (Analytical queries)
* **Tools**: Jupyter Notebook, GitHub

---

## 📂 Project Structure

```
HR-Attrition-Risk-Analytics/
│
├── data/
│   └── hr_attrition_final.csv
│
├── notebooks/
│   └── hr_attrition_ml_analysis.ipynb
│
├── powerbi/
│   └── HR_Attrition_Risk_Dashboard.pbix
│
├── sql/
│   └── attrition_analysis.sql
│
│
└── README.md
```

---

## 🔍 Methodology

### 1️⃣ Data Preparation

* Cleaned HR dataset and handled categorical variables
* Converted attrition target variable into binary format
* Performed exploratory data analysis and correlation analysis

### 2️⃣ Feature Engineering & Analysis

* Identified important features such as:

  * Job Level
  * Monthly Income
  * Years at Company
  * Job Satisfaction
  * OverTime

### 3️⃣ Machine Learning Model

* Built a **Random Forest Classifier** to predict attrition
* Handled class imbalance using balanced class weights
* Optimized decision threshold to improve **recall for high-risk employees**

### 4️⃣ Risk Scoring

* Generated **Retention Risk Scores (0–1)** for each employee
* Categorized employees into:

  * Low Risk
  * Medium Risk
  * High Risk

### 5️⃣ Power BI Dashboard

* Designed a **single-page dashboard** with:

  * Key HR KPIs
  * Risk distribution
  * Department-wise high-risk analysis
  * Estimated turnover cost

---

## 📊 Dashboard Highlights

* **Total Employees, Attrition Count & Attrition Rate**
* **High-Risk Employees by Department**
* **Employee Risk Distribution (Low / Medium / High)**
* **Estimated Turnover Cost**
* Interactive filters for:

  * Department
  * Job Role

---

## 💡 Key Insights

* Attrition risk is higher among employees with lower job levels and shorter tenure
* Certain departments show significantly higher high-risk concentration
* Early identification of high-risk employees can reduce turnover costs

---

## 📈 Business Impact

* Enables **proactive HR interventions** instead of reactive hiring
* Helps prioritize retention strategies for critical departments
* Provides **cost-based justification** for HR decisions

---

## 🚀 How to Use

1. Clone the repository
2. Review the Jupyter notebook for ML workflow
3. Open the Power BI `.pbix` file to explore the dashboard
4. Use filters to analyze department-level and role-level risks


---

## 📬 Contact

**Name:** Tanmay Manoj Bhole
**Email:** [tanmaybhole001@gmail.com](mailto:tanmaybhole001@gmail.com)

---

⭐ *If you found this project useful, feel free to star the repository.*
