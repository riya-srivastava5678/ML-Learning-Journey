# K-Nearest Neighbors (KNN)

## 📌 Overview

K-Nearest Neighbors (KNN) is a **supervised machine learning algorithm** used for both **classification and regression** problems.

KNN makes predictions based on the **closest data points (neighbors)** to a new data point.

In this project, I implemented KNN using **Python and Scikit-learn**, including data preprocessing, model training, prediction, and evaluation.

---

## 🧠 How KNN Works

KNN follows a simple approach:

1. Choose the value of **K** (number of neighbors).
2. Calculate the distance between the new data point and all training points.
3. Select the **K nearest data points**.
4. For classification, choose the class that appears most frequently among the neighbors.
5. For regression, calculate the average value of the neighbors.

### Example

If `K = 3` and the three nearest neighbors are:

```text
Class A
Class A
Class B
```

The prediction will be:

```text
Class A
```

because Class A has the majority.

---

## 📏 Distance Metric

KNN commonly uses **Euclidean Distance**:

$$
d = \sqrt{\sum_{i=1}^{n}(x_i-y_i)^2}
$$

The choice of distance metric can affect the performance of the model.

---

## ⚙️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Exploration
   ↓
Data Preprocessing
   ↓
Train-Test Split
   ↓
Feature Scaling
   ↓
KNN Model
   ↓
Hyperparameter Tuning
   ↓
Prediction
   ↓
Model Evaluation
```

---

## 📊 Feature Scaling

Feature scaling is particularly important for KNN because the algorithm is **distance-based**.

If one feature has a much larger numerical range than another, it can dominate the distance calculation.

Common scaling techniques include:

* StandardScaler
* MinMaxScaler

In this project, feature scaling was performed before training the KNN model.

---

## 🔧 Hyperparameter Tuning

The main hyperparameter in KNN is:

### `n_neighbors`

It determines how many neighboring data points are considered when making a prediction.

A small value of K can make the model sensitive to noise and may lead to **overfitting**.

A large value of K can make the model too generalized and may lead to **underfitting**.

Therefore, different values of K were tested to find a suitable value.

---

## 📈 Model Evaluation

For classification, the model can be evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

For regression, commonly used metrics include:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

---

## 📁 Project Structure

```text
KNN/
│
├── KNN.ipynb
├── README.md
└── dataset.csv
```

> File names may vary depending on the dataset and implementation.

---

## 💡 Key Learnings

Through this project, I learned:

* How KNN works internally
* Difference between classification and regression using KNN
* Importance of feature scaling for distance-based algorithms
* Effect of different values of K
* How to train and evaluate a KNN model
* How hyperparameter tuning improves model performance
* How to use Scikit-learn for machine learning implementation

---

## 🚀 Conclusion

KNN is a simple yet powerful machine learning algorithm, especially useful for problems where the relationship between data points can be captured through distance.

However, because KNN calculates distances to training points during prediction, it can become computationally expensive for large datasets.

This project helped me understand **distance-based machine learning algorithms and the importance of preprocessing and hyperparameter tuning**.

---

## 👩‍💻 Author

**Riya Srivastava**

B.Tech CSE (AI & ML)

Learning Machine Learning & Data Structures and Algorithms.
