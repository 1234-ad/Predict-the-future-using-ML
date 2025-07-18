# Predict the Future – Intro to Machine Learning

This project is part of a Data Science Internship task focused on building a simple supervised machine learning model.

## Task Overview

The objective is to predict the **price** of a product based on features like **category**, **size**, **demand**, and **base cost**.

## Steps Performed
- Generated a synthetic dataset with relevant features
- Preprocessed categorical features using Label Encoding
- Split the data into training and test sets
- Trained a **Linear Regression** model using `scikit-learn`
- Evaluated the model using **Mean Squared Error** and **R² Score**

## Dataset Features
- `Category`: Type of product (e.g., Electronics, Clothing)
- `Size`: Size category (Small, Medium, Large)
- `Demand`: Market demand (Low, Medium, High)
- `BaseCost`: Raw production cost
- `Price`: Final market price (target)

## Model Performance
- R² Score: 0.91
- MSE: 13,903.35

## How to Run
Open the notebook `Task_8_Predict_the_Future.ipynb` and run the cells sequentially.

---

Made with ❤️ by an intern.