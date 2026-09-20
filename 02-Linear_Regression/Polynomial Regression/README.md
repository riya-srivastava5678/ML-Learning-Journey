# Polynomial Regression

## 📌 Overview

Polynomial Regression is a supervised machine learning algorithm used to model non-linear relationships between independent variables and a continuous target variable.

Unlike Linear Regression, Polynomial Regression can fit a curved relationship between the features and target.

The general equation is:

y = β₀ + β₁X + β₂X² + ... + βₙXⁿ

---

## 🎯 Objective

The objective of this project is to implement Polynomial Regression and understand how polynomial features can be used to model non-linear relationships in data.

---

## 🔄 Workflow

The project follows these steps:

1. Import required libraries
2. Load the dataset
3. Explore the dataset
4. Perform data preprocessing
5. Select features and target
6. Split the data into training and testing sets
7. Create polynomial features
8. Transform the input features
9. Train the regression model
10. Make predictions
11. Evaluate the model
12. Visualize the regression curve

---

## 🤖 Model Used

### Polynomial Regression

Polynomial Regression extends Linear Regression by creating additional polynomial features such as:

- X
- X²
- X³
- ...

These additional features allow the model to capture non-linear patterns.

The implementation uses:

- `PolynomialFeatures`
- `LinearRegression`

from Scikit-learn.

---

## 📊 Evaluation Metrics

The model can be evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 📈 Linear vs Polynomial Regression

### Linear Regression

Used when the relationship between the features and target is approximately linear.

### Polynomial Regression

Useful when the relationship is non-linear and a straight line cannot adequately represent the data.

Increasing the polynomial degree can make the model more flexible, but a very high degree can lead to overfitting.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📁 Files

- `Polynomial_Regression.ipynb` — Complete implementation
- `README.md` — Project documentation

---

## 🧠 Key Learnings

Through this project, I learned:

- Difference between Linear and Polynomial Regression
- Creating polynomial features
- Understanding polynomial degree
- Model training and prediction
- Regression evaluation metrics
- Underfitting and overfitting
- Visualizing non-linear relationships