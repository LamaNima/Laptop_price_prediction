# Laptop Price Prediction using Machine Learning
## Overview
This project implements a machine learning model to predict laptop prices based on various features such as company, type, screen resolution, CPU, RAM, memory, GPU, operating system, weight, and screen size. The notebook includes data preprocessing, exploratory data analysis (EDA),feature engineering and model training using multiple regression algorithms, including 
Linear regression, Lasso regression, Ridge regression, KNN, Decision Tree, SVM, Random Forest, and AdaBoost. The goal is to identify the best-performing model for accurate price prediction.

## Project Structure
The notebook is organized into the following sections:

## Data Preprocessing:
- Loads the dataset and removes unnecessary columns (e.g., Unnamed: 0).
- Converts Ram and Weight columns to numeric formats by removing 'GB' and 'kg' suffixes.
- Verifies data integrity (no duplicates or missing values).

## Exploratory Data Analysis (EDA):
- Visualizes the distribution of the target variable (Price) using a histogram.
- Plotted individual relationships between the predictors and the target variable. 

## Feature Engineering:
- Extracted new features from the existing features more relevant for training model.
  (e.g. extracted ssd, hdd, hybrid, flash storage from memory column)

## Model Training and Evaluation:
- Implements multiple regression models using scikit-learn's Pipeline and ColumnTransformer for preprocessing.
- Categorical features are encoded using OneHotEncoder, and numeric features are scaled (where applicable) using StandardScaler.

Models evaluated include:
- Linear Regression
- Ridge Regression
- Lasso Regression
- K-Nearest Neighbors (KNN) Regression
- Decision Tree Regression
- Support Vector Machine (SVM) Regression
- Random Forest Regression
- AdaBoost Regression

## Dependencies
The project requires the following Python libraries:
- numpy
- pandas
- seaborn
- matplotlib
- scikit-learn

