# Elevate_Task16
A machine learning project demonstrating model optimization using GridSearchCV with cross-validation on the Breast Cancer dataset. Includes performance comparison between default and tuned models using Support Vector Machine (SVM).

This project demonstrates hyperparameter tuning in machine learning using GridSearchCV from Scikit-learn. The goal is to optimize a Support Vector Machine (SVM) classifier by systematically searching for the best combination of hyperparameters using cross-validation, and to compare the tuned model’s performance with a default model.

🧠 Learning Objectives

Understand the role of hyperparameters in machine learning models

Learn how to apply GridSearchCV for model optimization

Implement cross-validation correctly

Compare default and tuned model performance

Avoid common mistakes like tuning on test data

🧰 Tools & Technologies

Python

Scikit-learn

Pandas

Jupyter Notebook / Google Colab

📊 Dataset

Primary Dataset: Breast Cancer Dataset (from sklearn.datasets)

Problem Type: Binary Classification

Classes: Malignant, Benign

⚙️ Workflow

Load the dataset and apply basic preprocessing

Perform feature scaling using StandardScaler

Split data into training and testing sets

Train a default SVM model

Define a hyperparameter grid

Apply GridSearchCV with cross-validation

Extract best parameters and trained model

Evaluate and compare model performance
