
 # Breast Cancer Diagnosis: Benign vs Malignant using Logistic Regression (Binary Classification)


## 📌 Project Overview

This project focuses on predicting whether a breast tumor is **benign or malignant** using machine learning techniques. The dataset used is the **Wisconsin Diagnostic Breast Cancer (WDBC) dataset**.

The workflow includes data exploration, preprocessing, feature selection, model building, evaluation, and interpretation using a Logistic Regression model.

---

## 🎯 Objectives

* Perform exploratory data analysis (EDA)
* Preprocess and standardize features
* Handle class imbalance
* Build a Logistic Regression classification model
* Evaluate model performance using multiple metrics
* Interpret results for medical relevance

---

## 📊 Dataset Description

The dataset contains **569 samples** with **30 numerical features** extracted from digitized images of breast mass cells.

### Target Variable

* B → Benign (non-cancerous)
* M → Malignant (cancerous)

### Features Include

* Radius
* Texture
* Perimeter
* Area
* Smoothness
* Compactness
* Concavity
* Symmetry
* Fractal Dimension

Each feature is represented as mean, standard error, and worst values.

---

## ⚙️ Methodology

1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Feature Distribution Analysis
4. Correlation Analysis
5. Feature Selection (removing highly correlated features)
6. Train-Test Split
7. Feature Scaling (Standardization)
8. Baseline Model (Dummy Classifier)
9. Logistic Regression Model
10. Model Evaluation
11. ROC Curve and AUC Analysis
12. Interpretation of Results

---

## 🤖 Models Used

* Logistic Regression (main model)
* Dummy Classifier (baseline model)

---

## 📈 Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-score
* ROC-AUC
* Confusion Matrix

---

## 🏆 Results Summary

| Model               | Accuracy |
| ------------------- | -------- |
| Dummy Classifier    | ~63%     |
| Logistic Regression | ~97%     |

---

## 📊 Key Findings

* Malignant tumors tend to have higher values in radius, area, and perimeter
* Feature correlation was high and required removal of redundant features
* Standardization significantly improved model performance
* Logistic Regression provides strong interpretability for medical use
* The model performs well for binary classification of breast cancer

---

## ⚠️ Limitations

* Dataset size is relatively small
* Data may not fully represent real-world populations
* Logistic Regression assumes linear relationships
* Further validation is needed on external datasets

---

## 🚀 Future Improvements

* Apply cross-validation techniques
* Experiment with SVM, Random Forest, and XGBoost
* Improve feature engineering
* Deploy model using Flask or Streamlit
* Test on real clinical datasets

---

## 🛠️ Technologies Used

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 👨‍💻 Author

Rajab Ali

---
