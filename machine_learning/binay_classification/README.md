# 🚗 Binary Classification: Car Repainting Decision

**Course**: Machine Learning  
**University Project**

---

## 🧠 Project Overview

This project focuses on developing a binary classification model to assist a used car company in deciding whether a car should be repainted **white** or **not** (black). The goal is to predict the original color of each car (white or black) using various machine learning classification algorithms based on vehicle features.

The project follows a strict methodology to ensure explainability, clarity, and reproducibility, as outlined by the course guidelines.

---

## 📄 Dataset

The dataset originates from the [Kaggle Car Price Prediction Challenge](https://www.kaggle.com/datasets/deepcontractor/car-price-prediction-challenge), with the following modifications:

1. Rows with colors other than white or black were removed.
2. High-cardinality variables (ID, Model, Number of Doors) were excluded.
3. Categories with fewer than 625 observations were removed for the following features:
   - Manufacturer
   - Category
   - Fuel Type
   - Gearbox Type
   - Drive Wheels

**Target variable**:

- Derived from the `Color` column. The task is to predict whether a car should be repainted white (`1`) or not (`0`).

**Features used**:

- Selling Price
- Tax Amount
- Manufacturer
- Year
- Category
- Leather Interior
- Fuel Type
- Engine Volume
- Mileage
- Number of Cylinders
- Gearbox Type
- Drive Wheels
- Steering Position
- Number of Airbags

---

## ✅ Tasks and Methodology

### 1. 🔧 Data Cleaning & Feature Engineering

- Analyze and clean the dataset.
- Apply preprocessing and feature transformations where necessary.
- Justify each step as it relates to improving predictive performance.### 2. 🌳 Decision Tree Modeling

- Perform hyperparameter tuning to build the best classification tree.
- Use **four different validation metrics** to evaluate model performance.
- Visualize the best decision tree.
- Extract textual rules from the tree.
- Plot feature importance.

### 3. 🌲 Random Forest & XGBoost

- Conduct a grid search to find the optimal parameters for both models.
- Use **accuracy** as the evaluation metric.
- Compare performance against the decision tree.

### 4. 📊 Comparative Analysis

- Compare the selected models (Decision Tree, Random Forest, XGBoost).
- Analyze results, justify model selection, and reflect on performance trade-offs.

---

## 🗂️ Structure
