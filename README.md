# Project 1: Analysis of Customer Churn 🔍💻📊📈

This project analyzes customer churn in a telecom company using machine learning models. The data used for this project is publicly available from Kaggle (https://www.kaggle.com/blastchar/telco-customer-churn).

## Dataset 📋

The dataset contains information about telecom customers, including demographic information, services they subscribed to, account information, and whether or not they churned (i.e., canceled their service). There are a total of 7,043 customers in the dataset, and the churn rate is around 27%.

## Analysis 📊

The analysis is performed in a Jupyter notebook using Python 3. The notebook contains the following sections:

1. Exploratory Data Analysis (EDA) 🧐: This section explores the dataset to understand the distribution of variables, identify correlations between variables, and visualize the data.

2. Feature Engineering 🛠️: This section creates new features by combining or transforming existing features to improve the performance of machine learning models.

3. Model Selection 🤖: This section trains and evaluates several machine learning models, including Logistic Regression, Decision Tree, Random Forest, XGBoost, and Artificial Neural Networks (ANNs).

4. Model Tuning 🔧: This section fine-tunes the hyperparameters of the best-performing models to achieve the highest accuracy.

## Requirements 🛠️

The following Python packages are required to run the notebook:

- pandas 🐼
- numpy 🔢
- matplotlib 📈
- seaborn 🌊
- scikit-learn 🤖
- xgboost 🚀
- keras 🔥

## How to Run ▶️

To run the notebook, clone or download the repository to your local machine, navigate to the directory containing the notebook and run the following command:

```jupyter notebook```

Then open the notebook in your browser and run each cell sequentially.

## Conclusion 📝

The analysis shows that machine learning models can accurately predict customer churn in a telecom company. The best-performing model is the Artificial Neural Network, which achieves an accuracy of 81% on the test set. The analysis also reveals that factors such as contract type, payment method, and internet service are strong predictors of churn, and the company should focus on improving these areas to reduce churn.
