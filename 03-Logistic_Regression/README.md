# Logistic Regression - Personality Classification

## 📌 Overview

This project implements **Logistic Regression** for a personality
classification problem using a synthetic personality dataset.

The project covers the complete Machine Learning workflow, including:

- Data preprocessing
- Exploratory Data Analysis
- Feature selection
- Encoding categorical variables
- Feature scaling
- Train-test split
- Logistic Regression
- Model prediction
- Model evaluation
- Saving the trained model
- Saving the scaler for future predictions

---

## 🧠 What is Logistic Regression?

Logistic Regression is a supervised Machine Learning algorithm
primarily used for classification problems.

Instead of directly predicting a continuous value, Logistic Regression
predicts the probability of an observation belonging to a particular
class.

The model uses the **Sigmoid Function** to convert the linear output
into a probability between 0 and 1.

The general equation is:

`z = β₀ + β₁x₁ + β₂x₂ + ... + βₙxₙ`

The sigmoid function is:

`σ(z) = 1 / (1 + e⁻ᶻ)`

A classification threshold is then used to convert the probability
into a class prediction.

---

## 📊 Dataset

The project uses:

`personality_synthetic_dataset.csv`

The dataset contains synthetic personality-related observations
used to train and evaluate the classification model.

---

## ⚙️ Machine Learning Workflow

### 1. Data Loading

The dataset is loaded using Pandas.

### 2. Data Exploration

The dataset is explored to understand:

- Shape
- Data types
- Missing values
- Duplicate values
- Numerical features
- Categorical features
- Target distribution

### 3. Data Preprocessing

The data is prepared for Machine Learning by handling categorical
variables and preparing the features for model training.

### 4. Feature Encoding

Categorical variables are converted into numerical representations
so that they can be used by the Logistic Regression algorithm.

### 5. Feature Scaling

Numerical features are scaled before training the model.

A scaler is saved as:

`scaler.pkl`

This allows the same preprocessing transformation to be applied
when making predictions on new data.

### 6. Train-Test Split

The dataset is divided into training and testing sets.

The training set is used to train the model, while the testing set
is used to evaluate its performance on unseen data.

### 7. Model Training

A Logistic Regression classifier is trained using Scikit-learn.

### 8. Model Evaluation

The trained model is evaluated using classification metrics such as:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

---

## 💾 Saved Model

The trained Logistic Regression model is saved as:

`personality_model.pkl`

The scaler used during preprocessing is saved as:

`scaler.pkl`

These files can be loaded later to make predictions without
retraining the model.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Pickle

---

## 📂 Project Structure

```text
Logistic Regression/
│
├── logistic_solutions.ipynb
├── personality_synthetic_dataset.csv
├── personality_model.pkl
├── scaler.pkl
└── README.md