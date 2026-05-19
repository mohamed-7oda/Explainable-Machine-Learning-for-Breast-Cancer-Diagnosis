# 🧠 Explainable Machine Learning for Breast Cancer Diagnosis

This project focuses on building and evaluating multiple **machine learning models** for **breast cancer classification** using the **Wisconsin Diagnostic Breast Cancer (WDBC) dataset**, with a strong emphasis on **Explainable AI (XAI)** techniques.

---

## 📌 Overview

The goal of this project is not only to achieve high prediction accuracy, but also to **interpret and explain model decisions**, which is critical in sensitive domains like healthcare.

We implemented and compared several models, then applied advanced XAI techniques to understand **feature importance** and **model behavior**.

📄 Full report: 

---

## 📊 Dataset

* **Dataset:** Wisconsin Diagnostic Breast Cancer (WDBC)
* **Samples:** 569
* **Features:** 30 numerical features extracted from medical images
* **Classes:**

  * Malignant
  * Benign

---

## ⚙️ Project Pipeline

### 1. Data Preprocessing

* Data cleaning (no missing values)
* Robust scaling (to handle outliers)
* Feature selection using:

  * Mutual Information
  * ANOVA F-test
* Correlation-based feature reduction

### 2. Models Implemented

* Logistic Regression
* Linear Regression
* K-Nearest Neighbors (KNN)
* Random Forest
* Fuzzy Support Vector Machine (SVM)
* XGBoost
* Artificial Neural Network (ANN)

---

## 🏆 Results

* **Best Model:** Artificial Neural Network (ANN)
* **Accuracy:** ~97.3%
* **F1 Score:** ~97.5%

Other models like Random Forest and XGBoost also showed strong performance with better interpretability trade-offs.

---

## 🧠 Explainable AI (XAI)

To overcome the "black-box" problem, multiple explainability techniques were applied:

### 🔍 Global Explanations

* SHAP (feature importance & interactions)
* Partial Dependence Plots (PDP)
* ICE (Individual Conditional Expectation)

### 🔍 Local Explanations

* LIME (instance-level explanations)
* Gradient-based methods for ANN

📌 Key Insight:
Features like **area, concave points, and texture** were among the most influential in model predictions 

---

## 📈 Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC

All models were evaluated using a **70/15/15 train-validation-test split**.

---

## 🛠️ Technologies Used

* Python
* scikit-learn
* XGBoost
* TensorFlow / Keras
* SHAP
* LIME
* NumPy, Pandas, Matplotlib

---

## 📊 Key Insights

* Complex models (ANN, XGBoost) achieved the highest accuracy
* Simpler models (Logistic Regression, Random Forest) provided better interpretability
* XAI techniques significantly improved **trust and transparency** in predictions
* There is a critical trade-off between **performance and interpretability** in medical AI systems

---

## 🚀 Future Work

* Apply the pipeline to larger medical datasets
* Explore ensemble explainability techniques
* Integrate real-time explainability systems
* Add counterfactual explanations

---

## 👨‍💻 Author

**Mohamed Mahmoud Emam**
Machine Learning & AI Engineer
