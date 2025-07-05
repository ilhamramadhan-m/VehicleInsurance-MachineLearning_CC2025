# 🚗 Vehicle Insurance Customer Segmentation & Claim Prediction using Machine Learning

## 📌 Project Overview
This project utilizes the **Vehicle Insurance Customer Data** from Kaggle to extract insights using both **clustering (unsupervised learning)** and **classification (supervised learning)**. The objective is twofold:
- Identify distinct customer segments based on demographic and behavioral attributes.
- Predict whether a customer will claim vehicle insurance based on their profile.

This analysis is performed as part of the final submission for the **Belajar Machine Learning Pemula (BMLP)** program.

## 📂 Dataset
[Vehicle Insurance Customer Data — Kaggle](https://www.kaggle.com/datasets/ranja7/vehicle-insurance-customer-data/data)

The dataset contains features such as:
- **Demographics**: Age, Gender, Region, Driving License
- **Vehicle Info**: Previously insured, vehicle age, damage history
- **Policy Info**: Annual premium, policy sales channel
- **Target Variable**: `Response` — indicates if the customer showed interest in vehicle insurance

## 🧠 Analysis Breakdown

### Clustering Analysis
Notebook: `Vehicle Insurance Clustering Analysis.ipynb`

- **Objective**: Segment customers into groups for targeted marketing
- **Techniques**:
  - Feature scaling with MinMaxScaler
  - Dimensionality reduction using PCA
  - Clustering using **KMeans**
- **Model Evaluation**:
  - Optimal cluster number chosen via **Elbow Method** and **Silhouette Score**
  - Cluster visualization using 2D PCA projection

### Classification Analysis
Notebook: `Vehicle Insurance Classification Analysis.ipynb`

- **Objective**: Predict if a customer is likely to respond positively to an insurance offer
- **Preprocessing**:
  - Encoding categorical features
  - Feature-target split and train/test split
- **Models Used**:
  - Logistic Regression
  - Decision Tree
  - K-Nearest Neighbors (KNN)
- **Metrics Evaluated**:
  - Accuracy
  - F1-Score
  - Confusion Matrix
