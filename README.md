# 🧠 Task 5: Decision Trees and Random Forests

This project demonstrates the use of **Decision Trees** and **Random Forests** for binary classification using a heart disease dataset.

## 📌 Objective
To build, visualize, and evaluate classification models using decision trees and random forests, and to analyze model performance with and without pruning to avoid overfitting.

---

## 📁 Contents

| Section | Description |
|--------|-------------|
| 🔹 Introduction | Overview of the task and machine learning goals |
| 🔹 Data Loading | Load and inspect the `heart.csv` dataset |
| 🔹 Exploratory Data Analysis (EDA) | Check for missing values, get statistics, understand data |
| 🔹 Train-Test Split | Split the data into training and testing sets |
| 🔹 Decision Tree Classifier | Train and visualize a basic decision tree |
| 🔹 Overfitting Analysis | Plot accuracy vs. tree depth to identify optimal complexity |
| 🔹 Pruned Tree | Retrain using optimal depth to reduce overfitting |
| 🔹 Random Forest Classifier | Train a more robust ensemble model |
| 🔹 Feature Importance | Visualize which features matter most |
| 🔹 Cross-Validation | Compare models using 5-fold CV accuracy |

---

## 🛠️ Technologies Used

- Python 3
- pandas
- scikit-learn
- matplotlib
- graphviz (for tree visualization)

---

## 📊 Dataset

The dataset used is `heart.csv`, containing health metrics for predicting heart disease.

- Features: age, sex, chest pain type, resting BP, cholesterol, etc.
- Target: presence (1) or absence (0) of heart disease.

