# 🚗 Ford Car Price Prediction

This project predicts the **resale price of Ford cars** using **Machine Learning models**.
It involves **data preprocessing, exploratory data analysis (EDA), encoding, scaling, and model building** with regression algorithms.

## 🚀 Project Overview

The notebook performs the following steps:

1. **Importing Libraries** – Loading required Python libraries (pandas, numpy, sklearn, matplotlib, seaborn, etc.)
2. **Exploratory Data Analysis (EDA)** – Analyzing trends, correlations, and distributions of features.
3. **Encoding Data** – Converting categorical features into numerical values (Label Encoding / One-Hot Encoding).
4. **Scaling Data** – Applying normalization/standardization to improve model performance.
5. **Model Building** – Training machine learning models for car price prediction:

   * Linear Regression
   * Random Forest Regressor
6. **Model Evaluation** – Comparing models using metrics such as R² Score, RMSE, and MAE.

## 🛠️ Technologies Used

* Python
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn (Linear Regression, Random Forest)
* Jupyter Notebook

## 📂 Dataset

The dataset `ford.csv` contains information about used Ford cars, with features such as:

* **model** – Car model name
* **year** – Year of manufacture
* **price** – Selling price (Target variable)
* **transmission** – Type of transmission
* **mileage** – Distance driven
* **fuelType** – Type of fuel
* **tax** – Road tax
* **mpg** – Miles per gallon (fuel efficiency)
* **engineSize** – Engine size in liters

## 📈 Expected Insights

* Certain **models and years** have higher resale value.
* **Transmission type and fuel type** significantly impact price.
* Random Forest may perform better than Linear Regression due to handling non-linear patterns.

