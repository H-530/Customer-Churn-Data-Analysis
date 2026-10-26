# 📊 Customer Churn Data Analysis

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue.svg" alt="Python Version">
  <img src="https://img.shields.io/badge/Status-Completed-success.svg" alt="Project Status">
  <img src="https://img.shields.io/badge/License-MIT-green.svg" alt="License">
</p>

A comprehensive Data Science project using **Python** to analyze and predict customer churn in the banking sector. This project leverages **Exploratory Data Analysis (EDA)** techniques to uncover hidden patterns and relationships between customer demographics, behavior, and churn outcomes.

---

## 📌 Project Objective

To identify the key drivers responsible for customer churn in a retail bank using data visualization and statistical analysis, helping financial institutions design data-driven retention strategies and reduce customer attrition.

---

## 📁 Dataset Details

- **File:** `Bank_Churn.csv`
- **Source:** Public dataset (Simulated bank customer data)
- **Target Variable:** `Exited` (Churn: `1 = Yes`, `0 = No`)
- **Key Attributes:**
  - **Demographics:** Geography, Gender, Age
  - **Behavioral:** Tenure, NumOfProducts, HasCrCard, IsActiveMember
  - **Financial:** CreditScore, Balance, EstimatedSalary

---

## 🛠️ Tools & Libraries Used

* **Python 🐍** (Core language)
* **Pandas & NumPy** (Data manipulation & cleaning)
* **Matplotlib & Seaborn** (Data visualization)
* **SciPy** (Statistical analysis)

---

## 🔍 EDA Steps Performed

1. **Data Loading & Inspection:** Loaded the dataset, inspected data types, and checked for missing values or duplicates.
2. **Univariate Analysis:** Visualized the overall churn distribution (`Exited`).
3. **Demographic Analysis:** Explored the impact of Age, Gender, and Geography on churn rates.
4. **Behavioral Analysis:** Evaluated customer tenure, product usage, and active membership status.
5. **Financial Analysis:** Investigated correlations between Credit Score, Account Balance, Salary, and churn risk.
6. **Correlation Matrix:** Calculated Pearson correlation coefficients to identify feature collinearity.

---

## 💡 Key Insights

- **High-Risk Demographics:** Customers aged 40+ and inactive members showed significantly higher churn rates.
- **Geographic Disparities:** German customers exhibited a disproportionately higher churn rate compared to other regions.
- **Product Engagement:** The number of products held and tenure played a crucial role in determining customer loyalty.
- **Financial Indicators:** Interestingly, Estimated Salary and Credit Score showed minimal direct impact on churn likelihood in this dataset.

---

## 📈 Visualizations Included

- **Distribution Plots:** Bar and pie charts for churn proportion.
- **Categorical & Numerical Plots:** Countplots and histograms for demographics and behavior.
- **Outlier Detection:** Boxplots for financial patterns across churn classes.
- **Correlation Heatmap:** Visual representation of feature relationships.

---

## 📌 Future Scope

- Implement Machine Learning models for churn prediction
- Add customer feedback or transaction patterns
- Cluster customers based on risk profiles

---


## 📄 License

This project is open-source and free to use under the MIT License.
