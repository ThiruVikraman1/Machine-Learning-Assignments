# Machine Learning Assignments

This repository contains a collection of Machine Learning projects and assignments, focusing on implementing and optimizing various regression and classification algorithms.

## 📂 Project Structure

- **Regression Assignment/**
  - `insurance_pre.csv`: The dataset containing 1,338 records used for training and testing.
  - `Multiple_Linear_Regression.ipynb`: Implementation of baseline regression.
  - `Support_Vector_Machine.ipynb`: SVR implementation with hyperparameter tuning.
  - `Decision_Tree.ipynb`: DTR implementation using various depths and criteria.
  - `Random_Forest_Model_Deployment.ipynb`: The finalized, optimized model ready for deployment.

## 🚀 Project Highlight: Insurance Premium Prediction

The goal of this assignment was to develop a predictive model to estimate insurance charges based on individual parameters such as age, BMI, and smoker status.

### 📊 Dataset Overview
The dataset includes:
- **Features**: Age, Sex, BMI, Children, Smoker.
- **Target**: Charges (Insurance Premium).
- **Size**: 1,338 samples.

### 🛠️ Model Evaluation & Results
Extensive trial-and-error was performed across multiple algorithms to find the best-performing model based on the $R^2$ score.

| Algorithm | Best $R^2$ Score |
| :--- | :--- |
| Multiple Linear Regression | 0.78 |
| Support Vector Machine (SVR) | 0.81 |
| Decision Tree | 0.85 |
| **Random Forest (Optimized)** | **0.87** |

### 🏆 The Best Model
The **Random Forest Regressor** was selected as the final model for deployment with the following hyperparameters:
- **n_estimators**: 100
- **criterion**: 'squared_error'
- **max_features**: 'log2'

**Why this model?**
It achieved a peak accuracy of **87%**. By utilizing 100 trees and the `log2` feature selection method, the model provides a stable, high-performance prediction that effectively captures the non-linear relationships in the insurance data.

## 💻 Tech Stack
- **Language**: Python
- **Libraries**: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn, XGBoost.
- **Tools**: Jupyter Notebook.

---
Created by [Thiru Vikraman](https://github.com/ThiruVikraman1)
