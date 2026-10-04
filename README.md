# Task 2 - EDA Titanic Dataset | Elevate Labs Internship
By Rathnavath Mamatha

## Overview
Exploratory Data Analysis on Titanic dataset with 5 visualizations.

## Tools Used
Python, Pandas, Matplotlib, Seaborn, Google Colab

## Key Statistics
- Mean Age: 29.69, Median: 28, 177 missing values
- Mean Fare: 32.20, Max: 512.33, Std: 49.69
- Total: 891 passengers, Survival: 38%
- Nulls: Age 177, Cabin 687, Embarked 2

## Visualizations Created
1. Age Histogram - Most passengers 20-35 yrs, right-skewed
2. Fare Boxplot - Heavy outliers present, median 14.45
3. Correlation Heatmap - Pclass & Fare -0.55 negative correlation
4. Pclass vs Survived - 1st class 63% survived vs 3rd 24%
5. Sex vs Survived - Female 74% survived vs Male 19%

## Inferences & Insights
- Missing Age needs median imputation
- Fare needs log transformation due to high skewness (4.78)
- Sex and Pclass are strongest predictors of survival
- Outliers in Fare must be handled before ML model
- High multicollinearity between Pclass and Fare
