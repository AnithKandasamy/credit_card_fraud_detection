# Credit Card Fraud Detection

## Introduction

As a student aspiring to build a career in Data Science, i did this personal side project to apply my knowledge about Machine Learning algotithms on a concrete use case.

## Project Overview

This project aims to predict fraudulent credit card transactions using machine learning techniques. The dataset used for this project is the **Kaggle Credit Card Fraud Detection** dataset, which contains anonymized features and transaction information for over 280,000 credit card transactions, some of which are fraudulent.

## Dataset

The dataset is publicly available on Kaggle and consists of the following:

- **Features**: The dataset contains 30 anonymized features (`V1`, `V2`, ..., `V28`) along with two additional columns:
  - `Time`: The number of seconds elapsed between this transaction and the first transaction in the dataset.
  - `Amount`: The transaction amount.
  - `Class`: The target variable indicating if the transaction was fraudulent (1) or not (0).

## Objectives

The primary goal of this project is to:
- Detect fraudulent transactions using machine learning models.
- Explore and evaluate different models using appropriate metrics.

## Key challenges

Fraudulent transactions occur rarely in the real world, one of the key challenges was to deal with an imbalanced dataset with less than 0.2% of fraudulous transactions.
