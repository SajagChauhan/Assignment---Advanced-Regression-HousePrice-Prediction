# House Price Prediction Assignment


## Table of Contents
* [Problem Statement](#problem-statement)
* [Business Objective](#Business-objectives)
* [Approach Used](#Approach-used)
* [Observations & Results](#observations-&-results)



## Problem Statement
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

1. Which variables are significant in predicting the price of a house, and

2. How well those variables describe the price of a house.

## Business Objectives
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Approach Used
- Understanding the data.
- Perform the Data Cleaning.
- Perform Label Encoding & Visualization
- Visualize the Relationship Among the Variables (Categorical & Numerical)
- Created the Dummy Variables for Categorical Variables.
- Split the Data into Training and Testing Dataset.
- Perform Scaling of Features.
- Build the Linear Regression Model and see the R2 score Mertices.
- Build the Lasso and Ridge Regression Model to reduce model complexity.
- Observed the driving factors behind increase in Sale Price of House in Australia.   


## Observations & Results
From the above Analysis, We conclude that: 
Observations:

Top five features will be:
-GrLivArea
-OverallQual
-GarageCars
-OverallCond
-LotArea

1. OverallQual: if the overall quality of house is Excellant/very Excellent/Very Good. The Saleprice of house will increase by 0.145 to 0.18.
2. GrLivArea: if the living area above ground is more, Sale Price increases by 0.12 to 0.335.
3. GarageCars: if size of garage in car capacity increases. Then, SalePrice increases by 0.088 to 0.096.
4. OverallCond: if overall condition is Very Good/Excellent/Very Excellent. Then Sale Price increases by 0.070 to 0.078.
5. FullBath1: if bathroom is above ground increases. Then, SalePrice decreases by 0.059 to 0.047.
6. LotArea: if Lot size increases. Then, Saleprice increases by 0.059 to 0.066.


## Contact
Created by [@SajagChauhan] - feel free to contact me!