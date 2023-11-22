## Project Name
USHousing-AdvancedRegression

## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. 
The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. 
For the same purpose, the company has collected a data set from the sale of houses in Australia. 
The data is provided in the CSV file below.
The company is looking at prospective properties to buy to enter the market.
You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
The company wants to know: 
1.Which variables are significant in predicting the price of a house, and
2.How well those variables describe the price of a house.
Also, determine the optimal value of lambda for ridge and lasso regression.

You are required to model the price of houses with the available independent variables. 
This model will then be used by the management to understand how exactly the prices vary with the variables. 
They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns.
Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Conclusions
Conclusion 1 
The optimal value of alpha for ridge and lasso regression from the analysis is
Ridge Alpha is 1 
Lasso Alpha is 10

Conclusion 2 
R2 Score on the training data has decreased and has increased on the testing data.

Conclusion 3 
The predictors are the same but the coefficients of these predictors has altered.

Conclusion 4 
Since lasso's r2_score for the test dataset is marginally higher than lasso's, lasso regression will be used to address this issue.

Conclusion 5
The top five most important predictor variables:					
	1.11stFlrSF - First Floor square feet 
	2.GrLivArea - Above grade (ground) living area square feet
	3.Street_Pave - Pave road access to property
 	4.RoofMatl_Metal - Roof material_Metal
	5.RoofStyle_Shed - Type of roof(Shed)

Conclusion 6
In order to ensure that the test accuracy is equal to the training score, the model needs to be generalized. 
When applied to datasets other than the ones used for training, the model ought to yield reliable results. 
To ensure that the model's predicted accuracy is high, the outliers shouldn't be given undue weight. 
Only those outliers that are pertinent to the dataset should be kept after an outliers analysis has been completed to make sure this is not the case. 
The dataset has to have the outliers that don't make sense kept eliminated. A model cannot be relied upon for predictive analysis if it lacks robustness.

## Technologies Used
numpy - version 1.23.5
pandas - version 1.5.3
matplotlib - version 3.7.0
plotly - version 5.9.0
seaborn - version 0.12.2
statsmodels - version 0.13.5
sklearn - version 1.2.1
scipy - version 1.10.0

## Contact
Created by ssroy1 - feel free to contact me!

