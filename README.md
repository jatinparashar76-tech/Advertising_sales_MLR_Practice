# Advertising_sales_MLR_Practice
The main objective is to understand how Multiple Linear Regression works in a practical business scenario. Unlike Simple Linear Regression, which uses only one predictor, MLR considers multiple features simultaneously to estimate their combined relationship with sales.
# 📊 Advertising Sales MLR Practice

## 📌 Project Overview

**Advertising Sales MLR Practice** is a Machine Learning project based on **Multiple Linear Regression (MLR)** using Python.

The project analyzes the relationship between different advertising channels such as **TV, Radio, and Newspaper** and their impact on **Sales**. The main goal is to build a regression model that can use multiple input features to predict sales.

This project is created for practicing the complete basic Machine Learning workflow, from loading and understanding the data to training and evaluating a regression model.

---

## 🎯 Objectives

- Understand the concept of Multiple Linear Regression.
- Analyze advertising and sales data.
- Perform basic data preprocessing.
- Explore relationships between different variables.
- Train an MLR model.
- Predict sales using multiple features.
- Evaluate model performance using regression metrics.
- Understand regression coefficients.

---

## 🧠 Multiple Linear Regression

Multiple Linear Regression uses **two or more independent variables** to predict one dependent variable.

### Formula

```text
Sales = β₀ + β₁(TV) + β₂(Radio) + β₃(Newspaper)
```

Where:

- **Sales** → Target variable
- **TV** → TV advertising expenditure
- **Radio** → Radio advertising expenditure
- **Newspaper** → Newspaper advertising expenditure
- **β₀** → Intercept
- **β₁, β₂, β₃** → Model coefficients

---

## 🛠️ Technologies Used

- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📂 Project Structure

```text
Advertising_sales_MLR_Practice/
│
├── data/
│   └── advertising.csv
│
├── main.py
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Preprocessing
   ↓
Exploratory Data Analysis
   ↓
Correlation Analysis
   ↓
Feature Selection
   ↓
Train-Test Split
   ↓
Multiple Linear Regression
   ↓
Prediction
   ↓
Model Evaluation
```

---

## 📊 Data Analysis

The dataset is first loaded using Pandas and basic information is checked.

```python
import pandas as pd

data = pd.read_csv("data/advertising.csv")

print(data.head())
print(data.info())
print(data.describe())
```

The data is also analyzed using visualizations and correlation analysis to understand the relationship between advertising features and sales.

---

## 🤖 Model Building

The Multiple Linear Regression model is created using **Scikit-learn**.

```python
from sklearn.linear_model import LinearRegression

model = LinearRegression()

model.fit(X_train, y_train)

y_pred = model.predict(X_test)
```

The model learns the relationship between the advertising features and sales from the training data.

---

## 📏 Model Evaluation

The model performance can be measured using:

- **MAE** – Mean Absolute Error
- **MSE** – Mean Squared Error
- **RMSE** – Root Mean Squared Error
- **R² Score** – Measures the proportion of variation explained by the model

```python
from sklearn.metrics import (
    mean_absolute_error,
    mean_squared_error,
    r2_score
)

print("MAE:", mean_absolute_error(y_test, y_pred))
print("MSE:", mean_squared_error(y_test, y_pred))
print("RMSE:", mean_squared_error(y_test, y_pred) ** 0.5)
print("R2 Score:", r2_score(y_test, y_pred))
```

---

## 🎓 Key Learning Outcomes

Through this project, I practiced:

- Multiple Linear Regression
- Data preprocessing
- Exploratory Data Analysis
- Correlation analysis
- Feature selection
- Train-Test Split
- Model training
- Sales prediction
- Regression coefficients
- Model evaluation
- Data visualization

---

## 🔮 Future Improvements

- Add more features to improve the model.
- Perform detailed residual analysis.
- Check multicollinearity using VIF.
- Apply feature engineering.
- Compare MLR with other regression algorithms.
- Build an interactive Streamlit dashboard.

---

## 👨‍💻 Author

**Jatin Parashar**

Machine Learning & Data Science Learner 🚀

This project is part of my practical learning journey in **Machine Learning and Predictive Modeling**.

---

⭐ **If you find this project useful, consider giving it a star!**# 📊 Advertising Sales MLR Practice

## 📌 Project Overview

**Advertising Sales MLR Practice** is a Machine Learning project based on **Multiple Linear Regression (MLR)** using Python.

The project analyzes the relationship between different advertising channels such as **TV, Radio, and Newspaper** and their impact on **Sales**. The main goal is to build a regression model that can use multiple input features to predict sales.

This project is created for practicing the complete basic Machine Learning workflow, from loading and understanding the data to training and evaluating a regression model.

---

## 🎯 Objectives

- Understand the concept of Multiple Linear Regression.
- Analyze advertising and sales data.
- Perform basic data preprocessing.
- Explore relationships between different variables.
- Train an MLR model.
- Predict sales using multiple features.
- Evaluate model performance using regression metrics.
- Understand regression coefficients.

---

## 🧠 Multiple Linear Regression

Multiple Linear Regression uses **two or more independent variables** to predict one dependent variable.

### Formula

```text
Sales = β₀ + β₁(TV) + β₂(Radio) + β₃(Newspaper)
```

Where:

- **Sales** → Target variable
- **TV** → TV advertising expenditure
- **Radio** → Radio advertising expenditure
- **Newspaper** → Newspaper advertising expenditure
- **β₀** → Intercept
- **β₁, β₂, β₃** → Model coefficients

---

## 🛠️ Technologies Used

- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📂 Project Structure

```text
Advertising_sales_MLR_Practice/
│
├── data/
│   └── advertising.csv
│
├── main.py
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Preprocessing
   ↓
Exploratory Data Analysis
   ↓
Correlation Analysis
   ↓
Feature Selection
   ↓
Train-Test Split
   ↓
Multiple Linear Regression
   ↓
Prediction
   ↓
Model Evaluation
```

---

## 📊 Data Analysis

The dataset is first loaded using Pandas and basic information is checked.

```python
import pandas as pd

data = pd.read_csv("data/advertising.csv")

print(data.head())
print(data.info())
print(data.describe())
```

The data is also analyzed using visualizations and correlation analysis to understand the relationship between advertising features and sales.

---

## 🤖 Model Building

The Multiple Linear Regression model is created using **Scikit-learn**.

```python
from sklearn.linear_model import LinearRegression

model = LinearRegression()

model.fit(X_train, y_train)

y_pred = model.predict(X_test)
```

The model learns the relationship between the advertising features and sales from the training data.

---

## 📏 Model Evaluation

The model performance can be measured using:

- **MAE** – Mean Absolute Error
- **MSE** – Mean Squared Error
- **RMSE** – Root Mean Squared Error
- **R² Score** – Measures the proportion of variation explained by the model

```python
from sklearn.metrics import (
    mean_absolute_error,
    mean_squared_error,
    r2_score
)

print("MAE:", mean_absolute_error(y_test, y_pred))
print("MSE:", mean_squared_error(y_test, y_pred))
print("RMSE:", mean_squared_error(y_test, y_pred) ** 0.5)
print("R2 Score:", r2_score(y_test, y_pred))
```

---

## 🎓 Key Learning Outcomes

Through this project, I practiced:

- Multiple Linear Regression
- Data preprocessing
- Exploratory Data Analysis
- Correlation analysis
- Feature selection
- Train-Test Split
- Model training
- Sales prediction
- Regression coefficients
- Model evaluation
- Data visualization

---

## 🔮 Future Improvements

- Add more features to improve the model.
- Perform detailed residual analysis.
- Check multicollinearity using VIF.
- Apply feature engineering.
- Compare MLR with other regression algorithms.
- Build an interactive Streamlit dashboard.

---

## 👨‍💻 Author

**Jatin Parashar**

Machine Learning & Data Science Learner 🚀

This project is part of my practical learning journey in **Machine Learning and Predictive Modeling**.

---

⭐ **If you find this project useful, consider giving it a star!**
