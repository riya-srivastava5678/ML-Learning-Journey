# Linear Regression

## 📌 Overview

Linear Regression is a supervised machine learning algorithm used to predict a continuous numerical target variable.

It assumes a linear relationship between the input features and the target variable.

The basic equation is:

y = β₀ + β₁X

Where:
- y = predicted value
- β₀ = intercept
- β₁ = coefficient
- X = input feature

---

## 🎯 Objective

The objective of this project is to implement Linear Regression on a real-world dataset and evaluate its performance using regression evaluation metrics.

---

## 📂 Dataset

The project uses a Food Delivery Times dataset.

The dataset contains information related to food deliveries and factors that can affect delivery time.

The target variable is:

- Delivery Time

---

## 🔄 Workflow

The project follows these steps:

1. Import required libraries
2. Load the dataset
3. Explore the dataset
4. Perform data preprocessing
5. Handle missing values
6. Perform exploratory data analysis
7. Select features and target
8. Split the data into training and testing sets
9. Train the Linear Regression model
10. Make predictions
11. Evaluate the model

---

## 🤖 Model Used

### Linear Regression

Linear Regression finds the best-fitting straight line by minimizing the difference between actual and predicted values.

The model was implemented using:

`LinearRegression()` from Scikit-learn.

---

## 📊 Evaluation Metrics

The model can be evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

### R² Score

R² measures how well the model explains the variation in the target variable.

A value closer to 1 generally indicates better performance.

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

- `Linear_Regression SOL.ipynb` — Complete implementation
- `Food_Delivery_Times.csv` — Dataset
- `README.md` — Project documentation

---

## 🧠 Key Learnings

Through this project, I learned:

- How Linear Regression works
- How to prepare data for regression
- Train-test splitting
- Model training and prediction
- Regression evaluation metrics
- Interpreting model performance