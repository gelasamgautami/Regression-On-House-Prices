# Regression-On-House-Prices
Introduction
House prices increase every year, so there is a need for a system to predict house prices in thefuture. House price prediction can help the developer determine the selling price of a house andcan help the customer to arrange the right time to purchase a house. There are two factors thatinfluence the price of a house which include physical conditions and location. 
Data Exploration:

Summary Statistics The first step before performing any modeling is to look at the high-level summary of a dataset,understand the variablesand look for any abnormalities or hidden facts present in the data. Welook at summary statistics and distribution of the observations of each variable. It’s been observed that there are no missing values in the data.Calculate the minimum, maximum , mean, median, and standard deviation of ‘MEDV’, which is stored in prices.

A correlation matrix is a table showing correlation coefficients between variables. Each cellin the table shows the correlation between two variables. A correlation matrix is used as away to summarize data, as an input into a more advanced analysis, and as a diagnostic for
advanced analyses.From the above correlation matrix, we have found out that the attributes ‘RM’ and ‘LSTAT’play a significant role in predicting the house price as they possess a strong positive and anegative correlation respectively with the ‘MEDV’ value. So ‘RM’ and ‘LSTAT’ are thefeatures which we will use to fit our regression model. 
Box PLot:

A boxplot is a standardized way of displaying the distributionof data based on a five number summary (“minimum”, first quartile (Q1), median, thirdquartile (Q3), and “maximum”). It can tell you about your outliers and what their values are.We see that there are outliers in the variables ‘CRIM’, ‘ZN’ and ‘B’. Highest variability isobserved in the full-value property tax rates(TAX).
Scatter PLot:

A scatter plot is a type of diagram which represents the relationship between two variables. It isa two-dimensional data visualization that uses dots to represent the values obtained for twodifferent variables - one plotted along the x-axis and the other plotted along the y-axis.From the above scatter plots we can come know that the variables ‘RM’ has a positivecorrelation with the target value. As the number of rooms per dwelling increases, the houseprice also increases. Whereas, there is a negative correlation between the variable ‘LSTAT’ andthe target value(MEDV). As the people belonging to lower status increase, there is a decreasein the house price. Similarly for the attribute ÇRIM’, if the crime rate per capita increases thenthere is a decrease in price.
Regression Techniques:

Linear Regression,KNN,Support Vector Regression,Decision Tree, Randrom Forest.
From the above results, we found that K-Neighbors Regressor is the best algorithm for regression technique. Finally, we can see that K-Neighbors Regressor model achieved an impressive mean squared error of 16.335 which means our model is able to predict correct values o
n test data with MSE of 16.335.In the above, the scatter plot is plotted between the Y_Test and Predictions and we see that the predictedvalues and the test data for the target value that is the house prices almost coincide. That is they are scattered around the regression line fitted.
