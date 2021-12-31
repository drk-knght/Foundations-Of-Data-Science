# Foundations-Of-Data-Science

## Assignment- 1 ##
1. In this assignment, we will be implementing Polynomial regression (with degrees varying from 0,1, 2,. ., 9) using Gradient Descent and Stochastic Gradient Descent methods. But before implementing the algorithms, we will have to pre-process your data which includes shuffling the data, standardizing/normalizing the values and creating a random 70-30 split to aid in training and testing respectively. Vectorize your algorithms as much as possible to efficiently carry out the computations. Then print the error value after every 50 iterations during training for better visualization.


2. The dataset consists of two features i.e. ‘Strength’ and ‘Temperature’ applied to a certain piece of plastic. Using the features, we will predict how much ‘Pressure’ that the plastic can stand by constructing matured polynomial features and optimizing the weights by using GD and SGD without any regularization. Do the same for degrees 0, 1, 2, 3, 4, 5, 6, 7, 8, 9. Determine the which degree polynomial provides the best fit to the data. 


3. Using the same dataset, construct polynomial regression of degree 9 and implement ridge and lasso regression with gradient descent and stochastic gradient algorithms. Build both the models with for different values of lambda (5 values) and figure out the optimal models with the most appropriate lambda.
	
## Assignment- 2 ##
In this assignment, we have to use linear regression to predict house prices using the other 13 attributes (bedrooms, bathrooms, sqft_living etc.) of the dataset attached below. In order to achieve the same, you required to:-


	- Perform a thorough pre-processing of the dataset. The techniques you are expected to use include (but are not limited to) standardization, normalization, detecting outliers and handling missing values.
	- Perform greedy forward feature selection to find the subset of features that provide the optimal regression model. Find the minimum training and testing error of the optimal model obtained.
	- Perform greedy backward feature selection to find the subset of features that provide the optimal regression model. Find the minimum training and testing error of the optimal model obtained.
