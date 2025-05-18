# ✈️ Airline Passenger Satisfaction Prediction (CRISP-DM)

This project uses the CRISP-DM (Cross-Industry Standard Process for Data Mining) methodology to analyze airline passenger satisfaction and build predictive models using various machine learning algorithms.

---

## 📊 Project Overview

In the highly competitive airline industry, customer satisfaction is a major driver of customer retention and brand differentiation. This project aims to predict passenger satisfaction using a dataset of over 100,000 records and 24 features. We followed the CRISP-DM framework, conducted in-depth EDA using Tableau, and tested multiple models to identify key drivers of satisfaction.

---

## 🧠 CRISP-DM Phases

- **Business Understanding**: Why customer satisfaction matters in the airline industry.
- **Data Understanding**: Analysis of the raw dataset with 103,904 records and 24 features.
- **Data Preparation**: Feature engineering, binning, encoding, null handling, and scaling.
- **Modeling**: Trained and compared eight different ML models using feature subsets.
- **Evaluation**: Compared models on sensitivity, specificity, precision, G-mean, accuracy, and AUC.
- **Deployment Recommendations**: Suggested model strategies based on airline size and update cycles.

---

## 🚀 Models Used

We evaluated the following machine learning models:
- Random Forest
- XGBoost
- Logistic Regression (with Lasso)
- Decision Tree
- AdaBoost
- Support Vector Machine (SVM)
- Naive Bayes

### 🔍 Feature Selection Methods
- **Embedded**: Lasso, XGBoost, Random Forest
- **Wrapper**: Recursive Feature Elimination (RFE), Forward Feature Selection (FFS)
- **Filter**: Mann-Whitney U Test, Pearson’s Correlation

---

## 🥇 Best Model Scenarios

- **Scenario #5: XGBoost (Top 10 Features)**  
  Highest G-Mean and Precision, ideal for large airlines.
- **Scenario #2: Random Forest (Top 5 Features)**  
  More concise model, best for smaller carriers or quick deployment.

Key features across top models:
- Online Boarding
- Type of Travel
- Inflight WiFi Service
- Customer Type
- Inflight Entertainment

---

## 📈 Tableau Dashboard

All EDA visualizations were created using Tableau and can be explored at the following link:

👉 [Airline Satisfaction Tableau Dashboard](https://public.tableau.com/views/AirlineSatisfaction_17475269171530/Gender_Count?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## 📁 Dataset

> **Note**: The dataset used in this project was provided for academic purposes and cannot be shared publicly.

---

## 🛠️ Tools Used

- Python (Pandas, Scikit-learn, XGBoost)
- Tableau (EDA Visualizations)
- Jupyter Notebook
- CRISP-DM Framework
- Codespaces (GitHub cloud-based dev environment)

---

## 📌 Author

This project was completed as part of a university final Capstone Project.

