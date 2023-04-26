# Project Name : House Price Prediction assignment
> This is the case study for a advance understanding of multiple linear regression model using Lasso and Ridge.

## Table of Contents
* [General Info](#general-information)
* [Libraries Used in Python](#libraries-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements) 
* [Team Members](#teammembers)


## General Information <a name="general-information"></a>
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual value and flip them at a higher price. For the same purpose, the company has collected a data set from house sales in Australia. The data is provided in the csv file below.

The company is looking at prospective properties to buy to enter the market.

We are required to build a regression model using regularization, so as to predict the actual value of the prospective properties and decide whether to invest in them or not.

**The company wants to know:**

- Which variables are significant in predicting the price of a house

- How well those variables describe the price of a house

**Goal:**
We need to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

**We are going to solve the problem in 4 sections i.e. :**
- Data understanding and exploration
- Data Visualisation 
- Data preparation
- Model building and evaluation

## Libraries Used in Python <a name="libraries-used"></a>
- numpy 
- pandas
- matplotlib.pyplot
- seaborn 
- missingno
- sklearn
- statsmodels

## Conclusions <a name="conclusions"></a>
 Following are the observation and respective suggestion to consider while deciding house pricing:

- The higher values of positive coeeficients suggest a high sale value.

 |  Feature  |  Description  |
 |  ---  |  ---  |
 |  GrLivArea  |  Above grade (ground) living area square feet  |
 |  OverallQual  |  Rates the overall material and finish of the house  |
 |  OverallCond  |  Rates the overall condition of the house  |
 |  TotalBsmtSF  |  Total square feet of basement area  |
 |  PropAge   |Age of the property at the time of selling |
        
        
        
- The higher values of negative coeeficients suggest a decrease in sale value.

   |  Feature  |  Description  |
   |  ---  |  ---  |
   |  KitchenQual_TA  |  Kitchen quality as Typical/Average  |
   |  Foundation_CBlock  |  Type of foundation as Cinder Block  |
   |  HeatingQC_TA	  |  Heating quality and condition as Average/Typical |
    

- When the market value of the property is lower than the Predicted Sale Price, its the time to buy.

## Acknowledgements <a name="acknowledgements"></a>
- This project is given by Upgrad as an assignment case study
- All the data and requirements are provided by Upgrad.

## Team Members <a name="teammembers"></a>
Assignment done solely by Preity Rashmi
