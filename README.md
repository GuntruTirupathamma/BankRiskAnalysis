# BankRiskAnalysis
# 🏦 Bank Risk Analysis

This project performs a comprehensive **Bank Risk Analysis** using data related to customer applications, previous loan history, credit behavior, and demographic features. The objective is to identify potential **loan defaulters** and assess overall **credit risk**, helping financial institutions make more informed decisions.

---

## 📊 Table of Contents

- [About the Project](#about-the-project)
- [Data Overview](#data-overview)
- [Key Features](#key-features)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [Results & Visualization](#results--visualization)
- [Conclusion](#conclusion)
- [License](#license)

---

## 📌 About the Project

Credit risk is one of the primary challenges faced by banks. This project aims to:
- Identify key indicators that lead to loan defaults.
- Segment customers based on risk.
- Visualize important features affecting loan repayments.
- Assist banks in automating credit scoring.

---

## 🗃️ Data Overview

The project uses two primary datasets:

### `application_data.csv`
Contains customer demographic and financial info.

- Rows: 307,511
- Columns: 122

### `previous_application.csv`
Contains details of customers' past loan applications.

- Rows: 1,670,214
- Columns: 37

---

## 🔍 Key Features

- Null value analysis & imputation
- Feature engineering (e.g., external sources, housing type, credit amount)
- Correlation heatmaps
- Count plots for categorical columns grouped by target (`TARGET`)
- Risk categorization (Repayer vs Defaulter)
- Model building for risk prediction (Logistic Regression, Random Forest, etc.)

---

## 🛠️ Technologies Used

- **Python 3.10+**
- **Pandas**, **NumPy** – Data manipulation
- **Matplotlib**, **Seaborn** – Visualization
- **Scikit-learn** – ML models & preprocessing
- **Jupyter Notebook** or **VS Code**

---

