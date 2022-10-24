# Linear-Regression-Ocean-Salinity-Prediction
The temp_salinity.csv file contains data of ocean, its temperature and salinity. We have to predict the salinity of the water based on its temperature.
Perform regression analysis on the data, and answer the following questions.

#### 1. Plot a scatter plot of temp vs salinity. What is the relationship between them? 
#### 2. Calculate mean and standard deviation of salinity. Find out outliers(value greater than 2 standard deviations) in your data. List them down. 
#### 3. Filter out rows in your dataset, whose price is greater than 2 standard deviations. Plot a scatter of temp vs salinity, with outliers in a different color.
#### 4. Now split your filtered data with a 75:25 ratio using the train_test_split function. Perform linear regression with the training dataset. Plot the line of regression with the training data set. 
#### 5. Predict the output with the test data set. Find out the MSE, R^2 score. Plot a scatter of test output vs obtained output. 
#### 6. Perform another split of 80:20, and repeat steps 4 & 5. Which training yields a better score, Justify. 
#### 7. On the entire dataset, perform K Fold cross validation where k goes from 3-10. Print the average accuracy obtained for each value of k. 
