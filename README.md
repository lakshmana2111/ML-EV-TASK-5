# 🚗 ML Task 5 – EV Car Price Prediction Using Ridge Regression

## 📌 Project Overview

This project focuses on predicting the price of electric vehicles (EVs) in India using **Ridge Regression**.

The model uses important vehicle specifications and information, including:

* **Brand**
* **Model**
* **Range**
* **Power**
* **Battery**

The **Price** of the EV is used as the target variable for prediction.

---

## 🎯 Project Objective

The key objectives of this project are to:

* Explore and understand the EV dataset.
* Identify categorical and numerical features.
* Apply suitable data preprocessing techniques.
* Encode categorical variables using **One-Hot Encoding**.
* Scale numerical features using **StandardScaler**.
* Divide the dataset into training and testing sets.
* Build a **Ridge Regression** model.
* Experiment with multiple alpha values.
* Evaluate the model using standard regression metrics.

---

## 📂 Dataset

**Dataset Name:** EV Car India Dataset

The dataset contains information about electric vehicles available in the Indian market.

### 📊 Features

| Feature | Data Type   | Description                     |
| ------- | ----------- | ------------------------------- |
| Brand   | Categorical | Manufacturer or brand of the EV |
| Model   | Categorical | Specific EV model               |
| Range   | Numerical   | Driving range of the vehicle    |
| Power   | Numerical   | Power output of the vehicle     |
| Battery | Numerical   | Battery capacity                |
| Price   | Target      | Price of the electric vehicle   |

---

## 🛠️ Technologies & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab
* Jupyter Notebook

---

## 🔄 Machine Learning Workflow

```text
Import Dataset
      ↓
Understand & Explore Data
      ↓
Check Missing Values
      ↓
Define Features and Target
      ↓
Identify Categorical & Numerical Features
      ↓
Apply One-Hot Encoding
      ↓
Scale Numerical Features
      ↓
Train-Test Split
      ↓
Build Ridge Regression Model
      ↓
Experiment with Alpha Values
      ↓
Evaluate Model Performance
```

---

## ⚙️ Data Preprocessing

The dataset is divided into **input features** and the **target variable**.

### Categorical Features

* Brand
* Model

These features are transformed into numerical values using **OneHotEncoder**.

### Numerical Features

* Range
* Power
* Battery

These features are standardized using **StandardScaler**.

A **ColumnTransformer** is used to apply the appropriate preprocessing technique to each feature category.

---

## 🤖 Machine Learning Model

The project uses **Ridge Regression**, which is a regularized version of Linear Regression.

The following alpha values are tested:

```text
0.01
0.1
1
10
100
```

The **alpha** parameter controls the strength of regularization. T
