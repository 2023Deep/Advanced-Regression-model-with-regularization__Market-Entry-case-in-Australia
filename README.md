# Advanced Regression model with regularization: Market Entry case in Australia

Surprise Housing, a US-based real estate company, is expanding to the Australian market using data analytics. They've collected property sales data in Australia and aim to build a regression model with regularization to predict the actual values of potential properties. This model will guide investment decisions, helping the company identify lucrative opportunities and decide whether to enter the Australian real estate market.

## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)

## General Information

### Summary:
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

### Problem Statement:

The company wants to know:

- Which variables are significant in predicting the price of a house, and 
- How well those variables describe the price of a house ?
- Also, determine the optimal value of lambda for ridge and lasso regression.

## Conclusions
- The top five significant variables to predict the price of a house are 
    - GrLivArea :        
    - Overall Quality more than 9
        - OverallQual_9
        - OverallQual_10
    - GarageCars
    - OverallQual_8
    - Neighborhood type 
        - Neighborhood_NridgHt
        - Neighborhood_NoRidge
- From the R2 Score we can infer that the model can explain upto 89% variance

## Technologies Used
- Programming Language/s - Python
- Data Analysis Libraries - Numpy, Pandas
- Data Visualization Libraries - Matplotlib.pyplot, Seaborn
- Machine Learnign Libraries - Scikit-learn, SciPy
