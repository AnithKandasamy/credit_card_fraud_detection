# Credit Card Fraud Detection

## Introduction

As a student aspiring to build a career in Data Science, i did this personal side project to apply my knowledge about Machine Learning algotithms on a concrete use case.

## Key Concepts

Here are the key concepts addressed during this project :

  - **Exploratory Data Analysis (EDA)** : Exploration of the data, features and target distribution and correlation.
  - **Data Prepocessing** : Scaling of the data to apply needed algorithms and to optimize our models and spliting of test and train sets.
  - **Balancing of target class** : Synthesise fraudlent samples using SMOTE algorithm to improve our results.
  - **Logistic Regression** : Training, fitting and parameter tuning of our logistic regression model.
  - **Random Forest** : Training, fitting and analysis of features importance of our random forest model.
  - **Evaluation of models** : Evaluation using the F2 score which is the most suitable one for our problematic.

## Technologies used for this project

For this project, I used the Jupyter notebook environment within the VS Code IDE. 

Additionally, i used many libraries :
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- imbalanced-Learn

## Project Overview

This project aims to predict fraudulent credit card transactions using machine learning techniques. Moreover, we need to keep in mind that in fraud detection, it's generally better to wrongly flag a legitimate transaction as fraud (false positive) than to miss an actual fraudulent transaction (false negative), as missing fraud can lead to greater financial loss.

The dataset used for this project is the **Kaggle Credit Card Fraud Detection** dataset, which contains anonymized features and transaction information for over 280,000 credit card transactions, some of which are fraudulent.

## Dataset

The dataset is publicly available on Kaggle and consists of the following:

- **Features**: The dataset contains 28 anonymized features (`V1`, `V2`, ..., `V28`) along with three additional columns:
  - `Time`: The number of seconds elapsed between this transaction and the first transaction in the dataset.
  - `Amount`: The transaction amount.
  - `Class`: The target variable indicating if the transaction was fraudulent (1) or not (0).

## Objectives

The primary goal of this project is to:
- Detect fraudulent transactions using machine learning models.
- Explore and evaluate different models using appropriate metrics.

## Main challenge

Fraudulent transactions occur rarely in the real world, the key challenges was to deal with an imbalanced dataset with less than 0.2% of fraudulent transactions. This goes by applying sample synthesis algorithms like SMOTE to balance the dataset. It goes also by using suitable metrics to evaluate our models based on the imbalance of the dataset and the objectives of the credit card fraud detection particular use case.

## Results 

At the end, after trying the logistic regression model and the random forest, i managed to get a maximum of 81.24% F2 score thanks to the random forest.


![image](https://github.com/user-attachments/assets/1c6e373a-f3c3-42f9-8c14-f9c53c0edaf7)

## How to run this notebook

- Install the required Python libraries using this command :
```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
```

- Clone this project in your working directory
- Download the dataset from Kaggle using this [link](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) and move it in your working directory

## Possible Improvements 

To improve my results I can experiment more advanced boosting algorithms like XGBoost or LightGBM, which are known to perform well with imbalanced datasets. 




