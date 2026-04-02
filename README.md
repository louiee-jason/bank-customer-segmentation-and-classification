# Bank Customer Segmentation and Classification

End-to-end banking analytics project for customer segmentation and classification using clustering-based labeling and machine learning models.

## Overview
This project demonstrates a complete machine learning workflow that transforms unlabeled banking transaction data into meaningful insights and predictive models.
The pipeline combines unsupervised learning (clustering) and supervised learning (classification) to analyze customer behavior.

## Problem Statement
Banking systems generate large volumes of transaction data, but labeled data is often unavailable.

This project addresses that challenge by:
- Identifying customer segments using clustering
- Generating labels from cluster results
- Training classification models to predict customer behavior

## Pipeline
### 1. Data Preprocessing
- Data cleaning (handling missing values and duplicates)
- Feature encoding (Label Encoding and One-Hot Encoding)
- Outlier handling using IQR
- Feature scaling using StandardScaler
- Feature engineering through binning

### 2. Customer Segmentation
- Algorithm: K-Means Clustering
- Optimal cluster selection using Elbow Method and Silhouette Score
- Dimensionality reduction using PCA
- Cluster interpretation based on customer behavior

### 3. Label Generation
- Cluster results are converted into target labels
- Dataset prepared for supervised learning

### 4. Classification Modeling
- Decision Tree Classifier
- Random Forest Classifier
- Model evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1-score

### 5. Hyperparameter Tuning
- GridSearchCV applied to Random Forest
- Performance optimization

## Results
The project shows that clustering-based labels can be effectively used to train classification models for predicting customer segments.

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Joblib
