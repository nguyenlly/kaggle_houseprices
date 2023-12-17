# Housing Price Prediction Project

This repository contains the code for the attempts on Kaggle's House Prices Advanced Regression Competition. 

## Table of Contents
- [Goal](#goal)
- [Evaluation](#evaluation)
- [Getting Started](#getting-started)
  - [Import Library and Load Dataset](#import-library-and-load-dataset)
  - [Cleaning the Dataset](#cleaning-the-dataset)
  - [Exploratory Analysis](#exploratory-analysis)
- [Linear Regression Analysis](#linear-regression-analysis)
- [Polynomial Regression](#polynomial-regression)
- [Neural Network](#neural-network)

## Goal
The main goal of this project is to predict the sale prices for houses in the testing dataset based on the provided features. The project explores different regression techniques, including linear regression, polynomial regression, and neural network models.

## Evaluation
The model's performance is evaluated using the Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price.

## Getting Started
### Import Library and Load Dataset
- Data was imported from the Kaggle Competition into Google Colab. 
- Libraries Used: 
  - sys
  - matplotlib
  - numpy
  - pandas
  - seaborn
  - sklearn

### Cleaning the Dataset
- Removed variables with the highest amount of missing values. 
- Handled missing values by inputting the median for the NaNs.
- Used Label Encoder to create labels for categorical variables within the dataset.

### Exploratory Analysis
- Explored distribution of sale prices of houses and log-transformed to normalized.
- Looked into outliers within the dataset.
- Correlation test and isolate the top 15 variables with the highest correlation. 

## Linear Regression Analysis
- Conducted a Linear Regression Analysis on the training dataset.
- Model predicted house sale prices in the testing dataset with RMSE of 0.16567.

## Polynomial Regression Analysis
- Conducted a Polynomial Regression Analysis on the training dataset.
- Model predicted house sale prices in the testing dataset with RMSE of 0.15201. (Improvement from Linear Regression)

## Building a Neural Network
- Built a neural network and trained the model.
- After several configurations to hyper-parameters, the model predicted sale prices in the testing dataset with an RMSE of 0.53099. This is an improvement over the first initial model with an RMSE of 2.10037.

