# Battery SOH Prediction Using Machine Learning

## About the Project

This project focuses on predicting the **State of Health (SOH)** of Lithium-ion batteries using Machine Learning regression algorithms.

The main aim of this project is to analyze battery degradation data and predict the SOH of the battery based on its cycle-related data.

## Dataset

The dataset contains battery cycling and degradation-related information used for SOH prediction.

The data includes parameters such as:

* Battery Cycle
* Capacity
* Voltage
* Current
* Time
* SOH

## What I Did

* Loaded and explored the battery dataset
* Checked and cleaned the data
* Calculated the State of Health (SOH)
* Performed data analysis and visualization
* Selected the required features
* Split the data into training and testing sets
* Trained different Machine Learning regression models
* Predicted SOH using the trained models
* Compared the performance of different models

## Models Used

* Linear Regression
* Polynomial Regression
* Decision Tree
* Random Forest
* Gradient Boosting
* Support Vector Regression (SVR)

## Tools and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## Result

Different regression models were trained and their performance was compared using **R², MSE, RMSE, and MAE**.

**Gradient Boosting** gave the best performance with an **R² score of 0.9973**.

## Conclusion

This project helped me understand the application of Machine Learning in battery degradation analysis and SOH prediction, starting from data preprocessing and SOH calculation to model training, prediction, and performance evaluation.
