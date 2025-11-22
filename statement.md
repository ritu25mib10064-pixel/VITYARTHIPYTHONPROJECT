# Iris Dataset Classification – KNN, Logistic Regression & SVM

## Problem Statement
The goal of this project is to build and compare three classic machine learning classification models — K-Nearest Neighbors (KNN), Logistic Regression, and Support Vector Machine (SVM) — on the famous Iris flower dataset. The task is a multi-class classification problem: given four measurements of a flower (sepal length, sepal width, petal length, petal width), predict which of the three Iris species it belongs to (Setosa, Versicolor, or Virginica).

## Scope of the Project
This project covers the complete machine learning workflow:
- Exploratory Data Analysis (EDA) and visualization of the Iris dataset
- Data preprocessing (scaling, train-test split)
- Implementation and training of three models:
  - K-Nearest Neighbors (KNN)
  - Logistic Regression
  - Support Vector Machine (SVM with different kernels)
- Hyperparameter tuning using GridSearchCV / RandomizedSearchCV
- Model evaluation using accuracy, precision, recall, F1-score, and confusion matrix
- Side-by-side performance comparison of the three algorithms
- Visualization of decision boundaries (2D PCA projection)

The project is intentionally kept lightweight and educational, making it ideal for learning, teaching, or portfolio purposes.

## Target Users
- Data science / machine learning beginners who want to understand how classic algorithms work in practice
- Students taking introductory ML/AI courses
- Instructors looking for a simple yet complete example to demonstrate multiple algorithms on the same dataset
- Anyone building a portfolio project to showcase fundamental classification techniques

## High-Level Features
- Ready-to-run Jupyter notebook (`iris_classification_comparison.ipynb`) with detailed explanations
- Clean, visualizations, and commented code
- Comparative analysis table and charts showing performance metrics of KNN, Logistic Regression, and SVM
- Hyperparameter tuning results for each model
- 2D decision boundary plots using PCA for intuitive understanding of how each classifier separates the classes
- Reproducible environment setup via `requirements.txt`
- Easy to extend (add new models, try different datasets, etc.)

Start exploring the notebook and see how these three fundamental algorithms perform on one of the most famous datasets in machine learning!
