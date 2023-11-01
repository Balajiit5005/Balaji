Electricity Prices Prediction

Predicting electricity prices using machine learning and data analysis.

Overview
This project aims to predict electricity prices using machine learning techniques on the "Electricity.csv" dataset, available from [Kaggle](https://www.kaggle.com/datasets/chakradharmattapalli/electricity-price-prediction). Electricity price prediction is crucial for both consumers and suppliers in the energy market.

## Table of Contents

- [Installation]
- [Dependencies]
- [Usage]
- [Data Preprocessing]
- [Model Training]
- [Model Evaluation]

## Installation

1. Clone the repository:

    git clone https://github.com/sudeshsudhii/ADS_Phase1.git
  
2. Install the required Python libraries
    pip install -r requirements.txt

## Dependencies
This project depends on the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost
- lightgbm
- fbprophet
- tensorflow
- torch
- keras
You can install these dependencies by running the provided code file 

Usage
1.	Download the "Electricity.csv" dataset from [Kaggle](https://www.kaggle.com/datasets/chakradharmattapalli/electricity-price-prediction) and place it in the project root directory.
Also a dataset is provided on the git repository Electricity.csv.
2. Execute the code in your Python environment, such as Jupyter Notebook or your preferred IDE.
3. Customize the code to fit your specific dataset and requirements

## Data Preprocessing
Before training the models, ensure you've handled missing data, encoded categorical features, and performed necessary data transformations. Common data preprocessing steps include:
Handling Missing Data: Use techniques like mean imputation or removal of rows with missing values.
Encoding Categorical Data: Convert categorical features into numerical values using techniques like one-hot encoding or label encoding.
Feature Scaling: Standardize or normalize numerical features for better model performance.

## Model Training
This project uses various machine learning and deep learning models for electricity price prediction, including Linear Regression, Random Forest, XGBoost, LightGBM, Prophet, and deep neural networks. Customize the choice of model and hyperparameters to suit your specific use case.

## Model Evaluation
Evaluate the model's performance using metrics like Mean Squared Error (MSE) and R-squared (R2) on a test dataset. Visualize model predictions and performance metrics to gain insights into the model's performance.
