# 📊 K-Fold Cross Validation on Multiple Datasets with Model Comparison
## 📌 Project Overview

This project performs K-Fold Cross Validation on three different datasets:

Sonar Dataset

Iris Dataset

Diabetes Dataset

The objective is to preprocess each dataset, train multiple machine learning models, evaluate their performance using cross-validation, and determine the best suitable model for each dataset based on accuracy and consistency.

## 📂 Datasets Used
1️⃣ Sonar Dataset

Binary classification problem

Predicts whether an object is a mine or a rock

60 numeric features

2️⃣ Iris Dataset

Multi-class classification problem

Predicts species of iris flower

4 numeric features

3️⃣ Pima Indians Diabetes Dataset

Binary classification problem

Predicts likelihood of diabetes

Medical diagnostic attributes

## ⚙️ Data Preprocessing

The following preprocessing steps were applied:

✅ Removal of null/missing values

✅ Conversion of categorical/string labels into integers (Label Encoding)

✅ Feature scaling using Standardization (StandardScaler)

✅ Separation of features (X) and target variable (y)

Standardization ensures that all features have:

Mean = 0

Standard Deviation = 1

This improves performance for distance-based and gradient-based models.

## 🔁 Cross Validation Technique
K-Fold Cross Validation

Dataset split into K equal folds

Model trained on (K-1) folds

Tested on remaining fold

Process repeated K times

Final performance = Average of all folds

This approach:

Reduces overfitting

Provides reliable performance estimation

Ensures model stability

## 🤖 Models Implemented

The following classification algorithms were compared:

1️⃣ Logistic Regression

Linear classification algorithm

Suitable for linearly separable data

Efficient and interpretable

2️⃣ Support Vector Machine (SVM)

Maximizes margin between classes

Effective in high-dimensional spaces

Works well for complex decision boundaries

3️⃣ Random Forest

Ensemble learning method

Multiple decision trees

Reduces overfitting

High robustness

4️⃣ K-Nearest Neighbors (KNN)

Instance-based learning

Distance-based classification

Sensitive to feature scaling

## 📊 Model Evaluation Metric

Accuracy Score (Cross-Validation Mean Accuracy)

Comparison of average accuracy across folds

Stability across different datasets

## 🏆 Final Conclusion

After performing K-Fold Cross Validation on all datasets:

Sonar Dataset → Best suited model: (e.g., SVM / Random Forest depending on your result)

Iris Dataset → Best suited model: (e.g., Logistic Regression / Random Forest)

Diabetes Dataset → Best suited model: (e.g., Random Forest / Logistic Regression)

(Replace above with your actual results.)

The best model was selected based on:

Highest cross-validation accuracy

Stable performance across folds

Good generalization ability
