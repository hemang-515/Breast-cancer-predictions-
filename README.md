# KNN Classification Model 🔍📊

This project implements a **K-Nearest Neighbors (KNN)** classification model using Python.  
The goal of the project is to perform data preprocessing, exploratory data analysis (EDA), model training, evaluation, and prediction.

---

## 📌 Project Overview

This notebook includes:

- Importing and understanding the dataset  
- Data cleaning and preprocessing  
- Feature selection and scaling  
- Splitting the dataset into train/test sets  
- Training a **KNN classifier**  
- Evaluating performance using accuracy score  
- Making predictions  

---

## 🧠 About KNN Algorithm

**K-Nearest Neighbors** is a simple, non-parametric machine learning algorithm used for classification and regression.

How it works:

1. Select a value for **K** (number of neighbors).  
2. Calculate distance between the test point and training samples.  
3. Select the K nearest points.  
4. The majority class = prediction.

---

## 📊 Steps Performed in the Notebook

### ✔ Data Loading  
Reading the dataset using Pandas.

### ✔ Exploratory Data Analysis (EDA)  
- Checking data types  
- Handling missing values (if any)  
- Visualizing distributions  

### ✔ Preprocessing  
- Encoding categorical features (if needed)  
- Scaling numerical features using `StandardScaler`

### ✔ Model Training  
Using:
```python
from sklearn.neighbors import KNeighborsClassifier
