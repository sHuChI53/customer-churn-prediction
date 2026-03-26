# Customer Churn Prediction

## Project Overview

This project focuses on predicting telecom customer churn using machine learning. Customer churn prediction helps businesses identify customers who are likely to discontinue services so they can take proactive retention measures.

This project was completed as part of a Machine Learning assignment provided by Sabudh Foundation.

## Objective

The main objective of this project is to build a predictive model that identifies customers who are likely to churn based on historical telecom customer data.

## Dataset Description

The project uses multiple datasets:

* `1. customer_data.csv` – Contains general customer information
* `3. churn_data.csv` – Contains churn-related target variable
* `4. internet_data.csv` – Contains internet service usage details
* `2. Telecom Churn Data Dictionary.csv` – Describes dataset columns and meanings

These datasets are merged and processed to create the final modeling dataset.

## Features Used

The dataset includes the following types of features:

* Customer demographics
* Internet service details
* Contract type
* Payment method
* Tenure
* Monthly charges
* Total charges
* Service subscriptions
* Churn indicator

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Project Workflow

1. Data Loading
2. Data Cleaning
3. Handling Missing Values
4. Data Merging
5. Exploratory Data Analysis (EDA)
6. Feature Engineering
7. Encoding Categorical Variables
8. Train-Test Split
9. Model Building
10. Model Evaluation
11. Prediction

## Machine Learning Model

* Logistic Regression

## Model Evaluation Metrics

* Accuracy
* Confusion Matrix
* Classification Report
* Precision
* Recall
* F1 Score

## Repository Files

* `customer_data.csv`
* `churn_data.csv`
* `internet_data.csv`
* `Telecom Churn Data Dictionary.csv`
* `churn_prediction.ipynb`
* `README.md`

## How to Run the Project

1. Clone the repository
2. Install required libraries using pip
3. Open Jupyter Notebook
4. Run all cells in `churn_prediction.ipynb`

## Requirements

Install dependencies using:

```
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

## Future Improvements

* Try additional machine learning algorithms
* Perform hyperparameter tuning
* Add feature selection
* Deploy model using Streamlit or Flask
* Add interactive dashboard

## Author

Shuchi
