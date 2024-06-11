
# Real Estate Analysis 

![alt text](https://raw.githubusercontent.com/bulemi2/PPROJECT/main/Photo/todd-kent-178j8tJrNlc-unsplash.jpg)


## Multiple Regression Modeling

## Overview

This project involves a data analysis that focuses on examining housing prices. Its goal is to offer insights into the elements affecting housing prices by using a sample dataset.

### Target Audience
 
This data is of interest to a diverse set of stakeholders, including real estate agencies ,properties investors, homeowners, home sellers  and anyone keen on gaining insights into the housing market to help in making investment decisions.

# Business Understanding

# Introduction

The main goal of this project is to thoroughly analyze housing sales data using multiple regression models. We want to understand and measure how different factors relate to house prices. This analysis will provide valuable insights into what affects house prices, helping people involved in real estate, like homeowners and sellers. They can use the regression model to estimate their property's value and consider how specific changes can impact the price, making informed decisions about pricing and marketing strategies.

# Problem Statement

This project emphasizes the importance of pinpointing the key factors affecting house prices. Traditional methods rely on unreliable evidence, hindering our ability to predict and understand price changes accurately. To address this, we promote the extensive use of multiple regression models for analyzing housing sales data. These models help us uncover the relationships between different factors and house prices, considering the impact of multiple variables together.

# Main Objective

To use multiple regression modeling techniques to analyze house sales data with the aim of identifying and quantifying the influential factors affecting house sales prices. This analysis will empower stakeholders to make informed, data-driven decisions concerning their real estate investments.

# General Objectives

1. Explore the data to understand how different variables relate to the target variable, helping us choose relevant ones for the regression model.

2. Create a multiple regression model to predict house prices, considering chosen independent variables, checking model assumptions, ensuring a good fit, and making improvements as needed.

3. Analyze the coefficients of independent variables to find the most influential factors affecting house prices and describe their effects.

4. Check the model's performance to ensure accuracy and reliability.

5. Offer practical insights and recommendations for real estate investors and policymakers to make informed decisions, understand market trends, and contribute to effective economic planning.

# Data Understanding


The dataset used in this project contains information about the factors affecting housing prices, including variables such as date, sqft_above, view, and sqft_basement. Explanatory data analysis will be used to get a clear understanding of the dataset, including handling missing values, checking the data types, identifying outliers, and extracting relevant features for analysis.

# Results and interpretation

### Baseline Model:

 Mean Squared Error (MSE)

 The baseline model has a testing MSE of 0.0169, which signifies that its predictions have an average squared difference of approximately 0.0169 from the actual values. While this MSE is relatively low, it's higher than the Random Forest model's MSE.
 R-squared (R2) Score
The R-squared score for the baseline model is 0.6658, indicating that it explains around 66.58% of the variance in the target variable. This suggests a decent fit to the data, but there's still unexplained variance.

### Random Forest Regression Model

 Mean Squared Error (MSE)

 The Random Forest Regression model outperforms the baseline with a lower testing MSE of 0.0101. This indicates that the Random Forest model's predictions are, on average, closer to the actual values, which is a strong indicator of predictive accuracy.
R-squared (R2) Score 

The Random Forest Regression model have a higher R-squared score of 0.8201, signifying that it explains approximately 82.01% of the variance in the target variable. This is a substantially higher R-squared score compared to the baseline model.

The Random Forest Regression model demonstrates superior performance in terms of predictive accuracy compared to the baseline model. It achieves lower MSE and higher R-squared, which indicates that it provides more accurate and reliable predictions and explains a larger portion of the variance in the data.
The baseline model shows reasonable performance, but there's room for improvement, as indicated by a moderate R-squared score and a slightly higher MSE. It captures a portion of the variance in the data, but the Random Forest model excels in this regard.
The Random Forest model's results are particularly promising, making it a more robust and accurate choice for making predictions based on the provided metrics

## Conclusions

The Random Forest model excels with a notably low Mean Squared Error (MSE) of 
0.010 and Root Mean Squared Error (RMSE) of 0.100, outperforming the baseline and 
multilinear models. Its higher R-squared score of 0.82 indicates superior predictive 
accuracy, capturing around 82% of the data variability. These results collectively 
demonstrate the Random Forest model's stronger performance in predicting the 
price compared to the other models used.
