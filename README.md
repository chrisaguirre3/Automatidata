# Automatidata

### Description

Project working working with the NYC Taxi & Limousine Commission (TLC) to build a model that 
predicts taxi fares ahead of rides for an app they were building and to build a model that predicts whether or not customers would leave a tip to generate more revenue for taxi drivers.

### Problem Statement

How can we predict taxi fares and whether a customer will leave a tip ahead of rides?

### Task

Build, evaluate, and choose a predictive model that predicts taxi fares ahead of rides and another model that predicts whether a customer will leave a tip.

### The Dataset

- **Time Period:** 2017
- **Rows:** 22,699
- **Columns:** 18

<table style="border-collapse: collapse; border-spacing: 0; margin: 0; padding: 0;">
  <tr style="margin: 0; padding: 0;">
    <td style="margin: 0; padding: 0; border: none; align: left;">
      <img src="Automatidata Dataset Variables.png" alt="Dataset Variables" width="600" height="600" style="width:4000px;margin: 0; padding: 0; display: block;"/>
    </td>
  </tr>
</table>

[Link to Dataset](https://data.cityofnewyork.us/Transportation/2017-Yellow-Taxi-Trip-Data/biws-g3hs)

### Analysis Plan

1. Import necessary libraries/modules
2. Perform initial EDA
3. Conduct data cleaning
   - Nulls
   - Duplicates
   - Outliers
4. Perform full EDA
   - Data wrangling and feature engineering
5. Conduct A/B test to determine whether there is a relationship between payment type and fare amount
6. Build/evaluate Multiple Linear Regression model to predict taxi fares ahead of rides
7. Build/evaluate/choose between Random Forest and XGBoost models to predict whether a customer will leave a tip
8. Provide final recommendations/next steps

---

### Repository Files

- [Initial EDA](1.%20initial_eda.ipynb)
- [Data Cleaning, Wrangling, Feature Engineering, and EDA](2.%20data_cleaning_eda_visualizations.ipynb)
- [A/B Test](3.%20AB_test.ipynb)
- [Multiple Linear Regression Model](4.%20multiple_linear_regression.ipynb)
- [Feature Engineering and Machine Learning Models](5.%20feature_engineering_machine_learning.ipynb)
