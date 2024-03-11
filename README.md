# House prices prediction

***This repository contains implementation of Linear Regression models that predict the prices of houses based on their square footage and the number of bedrooms and bathrooms.***

# Dataset
The dataset is divided into 3 files for training, testing, and validation
It contains a large set of attributes that accurately describe the house, and based on these characteristics, the price of the house is determined.

 # Getting Started 
 ### Prerequisites
 -   Python 3.x
-  NumPy:  `!pip install numpy`
- sklearn:  `!pip install sklearn`
-  pandas:  `pip install pandas`

 # Linear Regression model
 
A linear regression model was used to predict the prices of houses based on their square footage and the number of bedrooms and bathrooms. 
To increase accuracy , two different methods were applied:
1. creating a set of new features resulting from merging more than one attribute in the dataset Such as 'BathRatio' resulting from 'FullBath', 'HalfBath' and 'TotRmsAbvGrd' attributes and also 'BedroomBathRatio' in the same way
2.  Use the GridSearchCV technique to increase the accuracy of the model by performing an exhaustive search over a specified parameter grid to find the optimal combination of parameters that minimizes the mean squared error (MSE) between the predicted and actual values.

Finally, the model was trained to be able to predict the price of the house based on the specified characteristics with MSE  **0.018**  for this Regression problem
