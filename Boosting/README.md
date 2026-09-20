# 🚀 Boosting

This folder contains my learning and implementation of **Boosting algorithms** as part of my Machine Learning journey.

## 📌 What is Boosting?

Boosting is an **ensemble learning technique** that combines multiple weak learners to create a strong predictive model.

Unlike Bagging, where models are trained independently, Boosting trains models **sequentially**. Each new model focuses more on the mistakes made by the previous models.

## ⚙️ How Boosting Works

1. Start with a simple/weak model.
2. Make predictions using the model.
3. Identify the errors or incorrectly predicted samples.
4. Give more importance to those difficult samples.
5. Train the next model to improve the previous model's mistakes.
6. Repeat this process for multiple models.
7. Combine the predictions of all models to produce the final prediction.

The goal is to gradually improve the overall performance of the model.

## 🧠 Important Boosting Algorithms

### 1. AdaBoost

**AdaBoost (Adaptive Boosting)** gives more weight to incorrectly classified samples so that subsequent models focus more on them.

### 2. Gradient Boosting

Gradient Boosting builds models sequentially, where each new model tries to reduce the errors made by the previous models using gradient descent.

### 3. XGBoost

**XGBoost (Extreme Gradient Boosting)** is an optimized and highly efficient implementation of gradient boosting.

It includes features such as:

* Regularization
* Parallel processing
* Handling missing values
* Efficient tree building

### 4. Other Boosting Algorithms

Other popular boosting algorithms include:

* LightGBM
* CatBoost

## 🔄 Boosting vs Bagging

| Boosting                              | Bagging                                   |
| ------------------------------------- | ----------------------------------------- |
| Models are trained sequentially       | Models are trained independently          |
| Each model focuses on previous errors | Each model learns from a different sample |
| Reduces bias                          | Mainly reduces variance                   |
| Can be more sensitive to noisy data   | Generally more robust to noise            |
| Examples: AdaBoost, Gradient Boosting | Example: Random Forest                    |

## 🔧 Important Hyperparameters

Some commonly used Boosting hyperparameters are:

* `n_estimators` – Number of weak learners/trees.
* `learning_rate` – Controls the contribution of each new learner.
* `max_depth` – Maximum depth of individual trees.
* `min_samples_split` – Minimum samples required to split a node.
* `min_samples_leaf` – Minimum samples required at a leaf node.
* `subsample` – Fraction of training data used for each boosting stage.

### Learning Rate

A smaller learning rate usually requires more estimators but can help the model learn more gradually.

For example:

```python
learning_rate = 0.1
n_estimators = 100
```

## 📊 Advantages

* Can produce highly accurate models.
* Converts weak learners into a strong learner.
* Works for both classification and regression.
* Can capture complex relationships in data.
* Often performs well on structured/tabular datasets.

## ⚠️ Disadvantages

* Training is sequential and can be slower.
* Can overfit if not properly tuned.
* Sensitive to noisy data and outliers in some implementations.
* Hyperparameter tuning can be important for good performance.

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## 📁 Files

```text
Boosting/
│
├── Boosting.ipynb
├── dataset.csv
└── README.md
```

## 🎯 What I Learned

Through this implementation, I learned:

* What ensemble learning means.
* How Boosting works.
* The difference between Bagging and Boosting.
* How weak learners are combined to create a strong learner.
* How AdaBoost works.
* How Gradient Boosting works.
* The importance of `learning_rate` and `n_estimators`.
* How to train and evaluate Boosting models using Scikit-learn.
* How hyperparameter tuning can improve model performance.

## 🚀 Machine Learning Journey

This project is part of my ongoing **Machine Learning journey**, where I am learning and implementing different Machine Learning algorithms step by step.

Currently exploring:

```text
Linear Regression
Logistic Regression
Decision Tree
Random Forest
K-Means Clustering
DBSCAN
NLP
Boosting
``` 
