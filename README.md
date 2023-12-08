# REG-Cricket

Follow the following steps and submit the final notebook in a GitHub repo.
1. Download the dataset named “IPL 2022 Batters.csv” from here
2. Read the data from the csv file using pandas data frame.
3. Check if there is any null value present in the data, if present handle them.
4. Plot graphs using matplotlib to explore various correlations in the data for example 
how the total run of a player is correlated to number of 4s hit or strike rate is 
correlated to the number of 4s hit.
5. Now you must perform linear regression on the number of 4s.
6. Create two data frames, one for features ( you may choose whichever columns you 
find suitable) and one for target (here target is number of 4s).
7. Now split the dataset using train_test_split utility from sklearn into training and 
testing with the number of 4s as a target.
8. Now train the linear regression model using sklearn on train data and predict the 
values for test data.
9. Find mean square error on train data predictions and test data predictions
10. Properly comment your code with markdown blocks, for each of the steps given 
abov
