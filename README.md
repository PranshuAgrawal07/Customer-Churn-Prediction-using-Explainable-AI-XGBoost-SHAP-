# 📉 Customer Churn Prediction using Explainable AI (XGBoost + SHAP)

<p align="center">

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-black?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-blue?logo=numpy)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?logo=scikit-learn)
![XGBoost](https://img.shields.io/badge/XGBoost-Gradient%20Boosting-success)
![SHAP](https://img.shields.io/badge/SHAP-Explainable%20AI-red)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blue)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Visualization-lightblue)

</p>

---

## 📌 Project Overview

Customer churn is one of the most critical business challenges faced by subscription-based businesses.

This project develops an **end-to-end Machine Learning pipeline** capable of predicting customer churn while providing transparent explanations using **SHAP Explainable AI**.

Unlike traditional churn prediction projects that focus solely on model accuracy, this project combines:

- Business Analytics
- Machine Learning
- Explainable AI
- Customer Retention Strategy

to generate actionable business recommendations.

---

# 🎯 Business Problem

Acquiring a new customer is significantly more expensive than retaining an existing one.

Telecommunication companies lose substantial revenue due to customer churn.

The objective of this project is to proactively identify customers likely to churn so that targeted retention strategies can be implemented before customers leave.

---

# 🚀 Project Objectives

- Predict customer churn using Machine Learning
- Identify major churn drivers
- Explain model predictions using SHAP
- Generate actionable business recommendations
- Build a recruiter-ready end-to-end ML project

---

# 📊 Dataset

**Dataset**

IBM Telco Customer Churn Dataset

Rows

7,043

Features

21

Target Variable

Churn

Problem Type

Binary Classification

---

# 🛠️ Tech Stack

| Category | Technologies |
|------------|----------------|
| Language | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Model | XGBoost |
| Explainability | SHAP |
| Model Persistence | Joblib |
| Notebook | Jupyter Notebook |

---

# 📂 Project Workflow

```

Dataset

↓

Data Understanding

↓

Data Cleaning

↓

Exploratory Data Analysis

↓

Feature Engineering

↓

Model Development

↓

Model Evaluation

↓

SHAP Explainability

↓

Business Insights

↓

Business Recommendations

↓

Model Deployment

```

---

# 📁 Repository Structure

```

Customer-Churn-Prediction/

│

├── notebook/

│ └── Customer Churn Prediction using Explainable AI.ipynb

│

├── model/

│ ├── customer_churn_xgboost.pkl

│ └── model_features.pkl

│

├── screenshots/

│ ├── churn_distribution.png

│ ├── feature_importance.png

│ ├── shap_summary.png

│ └── confusion_matrix.png

│

├── requirements.txt

├── README.md

```

---

# 📈 Exploratory Data Analysis

Major analyses performed

- Customer Demographics
- Contract Analysis
- Payment Method Analysis
- Internet Service Analysis
- Service Subscription Analysis
- Numerical Feature Analysis
- Correlation Analysis

---

# 🤖 Machine Learning Models

The following baseline models were evaluated:

| Model | Purpose |
|-----------|----------------|
| Logistic Regression | Baseline |
| Random Forest | Ensemble Comparison |
| XGBoost | Final Model |

Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

---

# 📊 Explainable AI (SHAP)

Instead of treating the ML model as a black box, SHAP was used to explain predictions.

Explainability includes:

- Feature Importance
- SHAP Summary Plot
- SHAP Waterfall Plot
- SHAP Dependence Plot

This enables business stakeholders to understand why customers are predicted to churn.

---

# 💡 Key Business Insights

✅ Long-term contracts significantly reduce churn.

✅ Customers using Fiber Optic Internet exhibit higher churn.

✅ Electronic Check payment method is associated with increased churn.

✅ Customers without Online Security are more likely to churn.

✅ Customers with low tenure represent the highest-risk customer segment.

---

# 📌 Business Recommendations

- Promote annual and two-year contracts.
- Launch early onboarding campaigns for new customers.
- Bundle Online Security with internet plans.
- Encourage automatic payment methods.
- Improve customer experience for Fiber Optic subscribers.

---

# 📊 Results

✔ Developed an end-to-end customer churn prediction pipeline.

✔ Compared multiple Machine Learning models.

✔ Selected XGBoost based on business requirements.

✔ Explained predictions using SHAP.

✔ Generated actionable business recommendations.

---

# 🔮 Future Enhancements

- Deploy using Streamlit
- REST API using FastAPI
- Real-time churn prediction
- Customer Lifetime Value Prediction
- Automated model retraining
- Cloud Deployment

---


