# ❤️ Heart Attack Risk Predictor

A collection of machine learning models and clustering techniques to **predict heart attack risk** based on medical indicators. This repo dives deep into supervised and unsupervised learning for potentially life-saving insight.

---

## 🧠 Overview

This project explores a variety of machine learning models to predict the risk of heart attacks using a dataset of patient health metrics like:

- Age
- Resting blood pressure
- Cholesterol
- Chest pain type
- Maximum heart rate
- ST depression
- Fasting blood sugar
- And more...

The goal? To train high-performing models that can classify patients by risk level, and to use clustering to discover patterns in unlabeled data.


## 🔍 Techniques Explored

- ✅ **Supervised Learning**
  - Decision Tree
  - K-Nearest Neighbors (KNN)
  - Gradient Boosting
  - Bagging

- 🔍 **Unsupervised Learning**
  - K-Means Clustering
  - DBSCAN for noise and anomaly detection

- ⚙️ **Preprocessing**
  - Missing value imputation
  - Feature scaling
  - One-hot encoding for categorical variables

---

## 📊 Sample Insights

- Patients over age 55 with high resting blood pressure and ST depression over 2.0 have a significantly elevated risk.
- Gradient Boosting outperformed other models with an accuracy of ~89% on the validation set.
- DBSCAN revealed a small cluster of outliers—potentially high-risk individuals not easily detected by classifiers.


