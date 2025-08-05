# 📊 Mortgage Loan Analysis & Delinquency Risk Prediction

This project conducts a comprehensive analysis of mortgage loan data from three critical years—**2008**, **2020**, and **2022**—capturing the evolving patterns before, during, and after financial stress periods. The analysis covers key indicators such as **Loan Age**, **LTV (Loan-to-Value)**, **Interest Rate**, and other financial metrics.

---

## 📌 Key Features

### 🔍 Year-by-Year Comparative Analysis
- Deep dive into loan characteristics in **2008**, **2020**, and **2022**
- Visual comparisons of distributions for:
  - **Loan Age**
  - **LTV**
  - **Interest Rate**
  - And more

### 🧠 Machine Learning: Delinquency Risk Prediction
- Predictive modeling of loan delinquency using:
  - `Logistic Regression`
  - `Random Forest`
  - `XGBoost`
- Evaluation metrics:
  - `F1 Score`
  - `Cross-validation`
  - `Feature Importance`

### 🧮 Loan-Level Interactive Analysis
- For a given **Loan Sequence Number**, the notebook:
  - Evaluates **refinancing potential**
  - Computes **breakeven period**
  - Offers tailored **recommendations**
- Includes an **interactive user interface** (via `ipywidgets`) to explore breakeven period calculations dynamically

---

## 📦 Tools & Libraries Used
- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `scikit-learn`, `xgboost`
- `ipywidgets` for interactivity
- Jupyter Notebook for full integration

---

## 🧠 Use Cases
- Understand mortgage trends across turbulent periods
- Assess refinancing strategy for individual loans
- Build or benchmark delinquency prediction models
- Financial education or fintech prototyping

---

## 💡 Future Improvements
- Integration with real-time or live mortgage data APIs
- More refined UI/UX for loan calculators
- Deployment as a standalone web app