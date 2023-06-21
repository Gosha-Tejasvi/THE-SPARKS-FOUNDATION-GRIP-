# THE-SPARKS-FOUNDATION-GRIP-
TASKS 

Title - Prediction using Simple Linear Regression in R
Problem - Predicting student's scores by the hours they study.

Using Simple Linear Regression to solve Task - 1 of my TSF Internship in Data Science & Business Analytics.

Independent Variable - Hours Dependent Variable - Scores Programming language - R Software - RStudio
Both are numeric values with one dependent variable so linear regression can be applied here.


Read CSV file using read.csv function

View and summarise the CSV file contents.

Using the lm() function, we fit a linear model on the dataset. Summarising the model gives us it's Coeffecients, Residuals, R squared value, P value, T and F test statistics and Slope and Intercept of regression line.

Plot the linear model using plot() function and add it's regression line using abline() function

Question in internship Task - 1: Predict the score if student studies for 9.25 hours a day? Store the hours whose score has to be predicted in a dataframe. Here i used as.data.frame() function to directly store the values in data frame named "p" Name column names of data frame as "Hours" using colnames() function Use predict() function to get the prediction of Scores if Hours of study is
92.90985

