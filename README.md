# AML-Basic-Project-Breast-Cancer#  

# Project Overview

This project uses machine learning to perform binary classification for breast cancer diagnosis. The model predicts whether a tumor is  **benign or malignant** based on numerical features from the **Wisconsin Diagnostic Breast Cancer Dataset**.

The implementation is done using Python and the Scikit-learn library, with Logistic Regression as the primary classification algorithm.

The goal of this project is to demonstrate how machine learning algorithms can be applied to structured medical data to build predictive models for breast cancer diagnosis
 
# DataSet

The dataset used in this project is the Wisconsin Diagnostic Breast Cancer (WDBC) Dataset, available from the UCI Machine Learning Repository.

The dataset contains measurements computed from digitized images of fine needle aspirate (FNA) of breast masses.

Dataset Information

**Total Samples**: 569

**Total Features**: 30 numerical features

Target Classes:

**M** – Malignant

**B** – Benign

Each feature describes characteristics of the cell nuclei, including:


Radius

Texture

Perimeter

Area

Smoothness

Compactness

Concavity

Symmetry

Fractal Dimension


# Key Challenges #

>Feature engineering for derived indicators (mean, standard error, worst values, etc.)

>Addressing class imbalance (357 benign vs 212 malignant samples)


# Workflow Overview

This version integrates a complete workflow covering hypothesis, EDA, baseline comparison, model building, and result interpretation. The report now uses Markdown + code blocks for clarity and readability.

 1. Hypothsesis

 2. Data Loading and Preliminary Exploration

 3.  Data Exploration (EDA)
 
 4. Data Preparations

 5. Baseline：Dummy Classifier
 
 6. Feature Standardization
  
 7. Logistic Regression Modeling
     
 8.  Result Evaluation 9. ROC Curve and AUC
  
 9.   Discussion

# Major Updates:

Baseline Model Introduction

Added a DummyClassifier as a benchmark.

Accuracy comparison: ~63% (Dummy) vs ~97% (Logistic Regression).


# Machine learning Module used

Two classification algorithms were implemented:

1.Logistic Regression 
2.Dummy Classifier (baseline model)

The dataset was split into training and testing sets using train_test_split.
Feature scaling was applied using StandardScaler.
Model performance was evaluated using confusion matrix, classification report, ROC curve, and AUC score.


# Other Supporting Librarier

These are used for data handling and visualization:

1. numpy

2. pandas

3. matplotlib

4. seaborn
   
5. Juptyer Note Book

6. Scikit-learn


# Enhanced Exploratory Data Analysis & Preprocessing

Visualized feature distributions, class imbalance, and correlation heatmaps.

Automatically removed highly correlated features (corr > 0.9) to reduce multicollinearity.

# Refined Report Structure

Clear modular format: Markdown explanations + code + interpretation.

# Expanded Results & Discussion

Discussed limitations, risks, and potential pipeline improvements.

Sets the stage for AML-Advanced projects.

# Additional Enhancements

Improved class imbalance handling

Stricter feature standardization

More comprehensive performance metrics

