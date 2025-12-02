# Machine Learning Models: Regression and Classification

This project applies four supervised learning algorithms to two public datasets from the UCI Machine Learning Repository.

| Task | Dataset| Target  | Models Used|
| ------ | ----- | ------ | ------ |
| **Regression** | [Automobile Dataset](https://archive.ics.uci.edu/dataset/10/automobile) | Car Price     | Linear Regression, SVM (regression), Decision Tree Regressor, MLP Regressor |
| **Classification** | [Heart Disease Dataset](https://archive.ics.uci.edu/dataset/45/heart+disease) | Heart Disease Presence (0/1) | Logistic Regression, SVM (classification), Decision Tree Classifier, MLP Classifier |

## Project Overview

This project demonstrates the application of supervised learning techniques to both regression and classification problems:

- **Regression:** Predicting car prices using numerical and categorical automobile features.  
- **Classification:** Predicting the presence or absence of heart disease based on patient attributes.


## Implementation Details

All models are implemented in **Python (3.13)** using the **scikit-learn** library.

### Models and Training

#### 1. Linear / Logistic Regression
- **Regression Task:** Predict car prices (Automobile dataset)  
- **Classification Task:** Predict heart disease presence (Heart Disease dataset)

#### 2. Support Vector Machine (SVM)
- **Regression:** `SVR(kernel = 'rbf')`  
- **Classification:** `SVC(kernel = 'rbf')`  
- **Parameter tuning:** C, gamma, and kernel choice

#### 3. Decision Tree
- **Regression:** `DecisionTreeRegressor()`  
- **Classification:** `DecisionTreeClassifier()`  
- **Criteria:** Gini impurity or information gain

#### 4. Multi-Layer Perceptron (Neural Network)
- **Regression:** `MLPRegressor(hidden_layer_sizes = (50, 50))`  
- **Classification:** `MLPClassifier(hidden_layer_sizes = (50, 50))`  
- **Activation functions:** ReLU, Logistic, or Tanh  
- **Optimizer:** Adam

---

## Evaluation Metrics

### Regression Models
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

### Classification Models
- Accuracy
- Precision, Recall, F1-score
- Confusion Matrix

Results are compared across models to determine the **best-performing algorithm** for each dataset.


How to Run

Follow the steps below to run this project locally.

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/ml-regression-classification.git
cd ml-regression-classification
```

### 2. Run the Jupyter notebooks