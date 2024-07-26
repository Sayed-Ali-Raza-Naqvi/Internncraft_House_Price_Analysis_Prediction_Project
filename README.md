# House Price Prediction Analysis and Prediction

## Overview
This project focuses on analyzing housing price data to build predictive models for estimating property values. The dataset contains various features such as property type, location, area, number of bedrooms and baths, and price. The goal is to explore the data, prepare it for modeling, and evaluate different machine learning algorithms to predict housing prices.

## Introduction
This project aims to analyze housing price data and build predictive models to estimate housing prices. It involves understanding the dataset, cleaning and preparing the data, performing exploratory data analysis (EDA), and building machine learning models.

## Data Overview
### - Load the Data
The dataset is loaded and examined to understand its structure, including a sample of the data and basic statistics.

### - Dataset Shape and Information
The shape and general information about the dataset are reviewed to assess the amount and type of data available.

## Data Cleaning and Preparation
### - Drop Unnecessary Columns
Irrelevant or excessive columns are removed from the dataset to streamline the analysis.

### - Convert Area Units
Area measurements are standardized from different units to square feet for consistency.

### - Feature Engineering
New features are created to enhance the model, including total rooms, price per square foot, and age of the property.

## Exploratory Data Analysis (EDA)
### - Initial Data Overview
Basic statistics and feature distributions are reviewed to understand the data's characteristics.

### - Univariate Analysis
The distribution of numerical and categorical features is analyzed through histograms and count plots.

### - Bivariate Analysis
Relationships between features and the target variable (price) are examined using scatter plots and correlation matrices.

### - Box Plots for Categorical Features
Price distributions are visualized across different categorical features to identify patterns.

### - Outlier Detection and Removal
Outliers are detected and removed using Interquartile Range (IQR) and Isolation Forest techniques. The data is also transformed using logarithmic functions for better model performance.

## Modeling
### - Data Preparation
Numerical features are scaled, and categorical features are label-encoded to prepare the data for modeling.

### - Linear Regression
A Linear Regression model is trained and evaluated to establish a baseline performance.

### - Random Forest Regression
A Random Forest Regressor is applied to the data, and its performance is assessed using metrics such as RMSE and R^2 score. The percentage error is also calculated to understand the model's accuracy.

### - XGBoost Regression
An XGBoost Regressor is trained and evaluated to compare its performance with other models.

## Conclusion
In this project, we conducted a comprehensive exploratory data analysis, handled outliers, and built multiple predictive models for housing prices. The performance of each model was assessed using RMSE and R^2 score to determine their effectiveness in predicting property values.

## Acknowledgements
Dataset: Provided by Internncraft
Libraries: scikit-learn, XGBoost, pandas, numpy, matplotlib, seaborn
