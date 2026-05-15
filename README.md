
 # Breast Cancer Diagnosis: Benign vs Malignant using Logistic Regression (Binary Classification)


## 📌 Project Overview

This project focuses on building a **binary classification model** to detect whether a breast tumor is **benign or malignant** using the **Wisconsin Diagnostic Breast Cancer dataset**.

The workflow includes **EDA, preprocessing, feature selection, model training, evaluation, and interpretation** using a Logistic Regression model.

---

## 🎯 Objective

* 🔍 Analyze breast cancer dataset using EDA
* 🧹 Preprocess and standardize features
* ⚖️ Handle class imbalance
* 🤖 Build a Logistic Regression classifier
* 📊 Evaluate model performance
* 🧠 Interpret results for medical relevance

---

## 📂 Dataset Information

* 📊 Source: Wisconsin Diagnostic Breast Cancer (WDBC) Dataset (UCI Repository)
* 🔢 Samples: 569
* 📈 Features: 30 numerical features extracted from FNA images

### 🎯 Target Classes

* 🟢 `B` → Benign (Non-cancerous)
* 🔴 `M` → Malignant (Cancerous)

---

## 📌 Key Features

* Radius
* Texture
* Perimeter
* Area
* Smoothness
* Compactness
* Concavity
* Symmetry
* Fractal Dimension

Each feature is provided as **mean, standard error, and worst values**.

---

## ⚙️ Workflow

1. 📥 Data Loading
2. 🔍 Exploratory Data Analysis (EDA)
3. 📊 Feature Distribution Analysis
4. 🔗 Correlation Heatmap
5. 🧹 Feature Selection (Remove high correlation > 0.9)
6. ⚖️ Handling Class Imbalance
7. ✂️ Train-Test Split
8. 📏 Feature Scaling (Standardization)
9. 🤖 Model Training (Logistic Regression)
10. 🧪 Baseline Model (Dummy Classifier)
11. 📊 Model Evaluation
12. 📈 ROC Curve & AUC Analysis
13. 🧠 Model Interpretation

---

## 🤖 Models Used

* 📈 Logistic Regression (Main Model)
* 🧪 Dummy Classifier (Baseline Model)

---

## 📊 Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-score
* ROC-AUC
* Confusion Matrix

---

## 🏆 Results Summary

| Model                  | Accuracy |
| ---------------------- | -------- |
| 🧪 Dummy Classifier    | ~63%     |
| 📈 Logistic Regression | ~97%     |

---

## 📊 Key Insights

* 🧬 Malignant tumors show higher values in radius, perimeter, and area
* 🔗 Strong correlation exists between multiple features (handled via feature removal)
* 📏 Feature scaling significantly improves Logistic Regression performance
* 🤖 Logistic Regression provides strong accuracy + interpretability for medical use
* ⚖️ Class imbalance handling improved model reliability

---

## ⚠️ Limitations

* 📉 Dataset size is relatively small (569 samples)
* 🔗 High feature correlation required careful preprocessing
* 🏥 Model needs external validation for real-world deployment
* ⚖️ Logistic Regression assumes linear decision boundaries

---

## 🚀 Future Improvements

* 🔁 K-Fold Cross Validation
* 🤖 Advanced models (SVM, XGBoost, Random Forest)
* 🧠 Feature engineering for better clinical interpretation
* 🌐 Deploy using Streamlit / Flask
* 🏥 Test on real hospital datasets

---

## 🛠️ Technologies Used

* 🐍 Python
* 📊 Pandas, NumPy
* 📉 Matplotlib, Seaborn
* 🤖 Scikit-learn
* 📓 Jupyter Notebook

---

## 👨‍💻 Author

**Rajab Ali**




