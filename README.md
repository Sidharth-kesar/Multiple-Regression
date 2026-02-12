# 📊 Polynomial Regression in Python

This repository contains an implementation of **Polynomial Regression** using Python and scikit-learn.  
The project demonstrates how non-linear relationships in data can be modeled by transforming features and applying linear regression.

Despite the name, polynomial regression is still **linear regression applied on transformed features**.

---

## 🔍 Problem Statement

Simple Linear Regression assumes a straight-line relationship between variables.  
However, many real-world datasets exhibit **non-linear patterns**.

This project shows how **Polynomial Regression** can better fit such data by increasing model flexibility while still using linear regression internally.

---

## 🧠 Concepts Covered

- Limitations of Simple Linear Regression
- Non-linear data behavior
- Polynomial feature transformation
- Effect of polynomial degree on model performance
- Overfitting vs underfitting
- Model visualization and comparison

---

## 🛠️ Tech Stack

- Python 3
- NumPy
- Pandas
- Matplotlib
- scikit-learn

---

## 📂 Dataset

- The dataset consists of:
  - Independent variable (X)
  - Dependent variable (y)
- The relationship between X and y is **non-linear**

This dataset is used to highlight the failure of linear regression and the improvement achieved using polynomial regression.

---

## ⚙️ Project Workflow

1. Import required Python libraries  
2. Load and explore the dataset  
3. Visualize data to detect non-linearity  
4. Apply Simple Linear Regression as a baseline  
5. Transform input features using `PolynomialFeatures`  
6. Train the Polynomial Regression model  
7. Compare linear vs polynomial regression  
8. Visualize regression curves  

---

## 📊 Visualizations

The notebook generates:
- Scatter plot of original data points
- Linear regression line
- Polynomial regression curve
- Visual comparison between models

These plots help in understanding model behavior and identifying overfitting.

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
