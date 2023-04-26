# House price prediction using Advanced Regression
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.
We are building a model for the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns.


## Table of Contents
* Goal
* Conclusions
* Technologies Used
* Contact



## Goal
The company wants to know:

- Which variables are significant in predicting the price of a house
- How well those variables describe the price of a house



## Conclusions
- Lasso regression model with alpha=0.0001 seems to work best for us taking in consideration the complexity of the model.
- The most important features of the model are- BsmtFullBath, LowQualFinSF, OverallCond, RemodAge, MasVnrArea.
- The model explains approximately 87% of the variance in the price for the test data



## Technologies Used
- numpy- 1.21.5
- pandas - 1.4.4
- seaborn - 0.11.2
- matplotlib - 3.5.1
- sklearn - 1.0.2




## Contact
Created by [@Nancy_bhutani] - feel free to contact me!
