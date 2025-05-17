# ✈️ Airline Passenger Satisfaction Prediction (CRISP-DM)

This project uses the CRISP-DM (Cross-Industry Standard Process for Data Mining) methodology to analyze airline passenger satisfaction and build predictive models using machine learning.

### 🧠 CRISP-DM Phases
- **Business Understanding**
- **Data Understanding**
- **Data Preparation**
- **Modeling**
- **Evaluation**
- **Deployment Recommendations**

---

## 🚀 Project Overview

Airline customer satisfaction is vital in a competitive market. This project leverages machine learning to identify key drivers of satisfaction using a dataset of over 100,000 passenger records with 24 features. The analysis included:

- EDA with Tableau
- Feature engineering and encoding
- Data balancing using SMOTE and undersampling
- Feature selection using wrapper, filter, and embedded methods
- Predictive modeling using Random Forest, XGBoost, Logistic Regression, SVM, Naive Bayes, Decision Tree, AdaBoost

### 🎯 Goal

Predict customer satisfaction (satisfied vs. not satisfied) based on various features like service quality, delay time, comfort, and travel type.

---

## ⚙️ Methods

- **Models**: Random Forest, XGBoost, Logistic Regression, Decision Tree, SVM, AdaBoost, Naive Bayes
- **Feature Selection**: RFE, FFS, Lasso, Mann-Whitney U Test, Pearson’s Correlation
- **Metrics**: Accuracy, Precision, Sensitivity, Specificity, G-Mean, AUC

---

## 📊 Results

Best-performing models:
- ✅ **Scenario #5** (XGBoost with 10 features): Best G-Mean and Precision
- ✅ **Scenario #2** (Random Forest with 5 features): Best performance for simpler model

Key Features:
- Online Boarding
- Type of Travel
- Inflight WiFi Service
- Customer Type
- Inflight Entertainment

---

## 📁 Dataset

> **Note**: The dataset used in this project was provided for academic purposes and cannot be shared publicly due to institutional guidelines.

---

## 📦 Tools Used

- Python (Pandas, Scikit-learn, XGBoost)
- Tableau (for visualization)
- Jupyter Notebook
- CRISP-DM Methodology

---

## 📌 Authors

This project was completed as part of a university Machine Learning course.
