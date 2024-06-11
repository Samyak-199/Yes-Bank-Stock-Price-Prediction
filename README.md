# Yes-Bank-Stock-Price-Prediction

PROBLEM STATEMENT : **Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. Owing to this fact, it was interesting to see how that impacted the stock prices of the company and whether Time series models or any other predictive models can do justice to such situations. This dataset has monthly stock prices of the bank since its inception and includes closing, starting, highest, and lowest stock prices of every month. The main objective is to predict the stock’s closing price of the month.

PROJECT SUMMARY :
The Dataset contains information about the YES BANK Stock Prediction.We have 185 rows and 5 columns in our Dataset. We are having columns- Date, Open, Close, High, Low.
**In a first step, I have imported the dataset through pandas ’read_csv’ then performed the Data wrangling over the raw data
after that, I have divided the whole data set into various groups like feature engineering, Univariate analysis, Bivariate analysis and divide the model into various regressions.**

As there is no null values in the dataset we didn't got a chance to replace or remove the null values. Also we have find out the outlier with the help of boxplot.
** firstly we have gone through the opening and closing stock prices with the help of line graph for the last three years then we have drawn a scatter plot in which we have done yearly analysis of the opening and closing stock for all years.**
After that I have done a graphical representation of the dependent and independent variables. And find out the relationship between dependent and independent variable.
Now, I have checked the correlation among each using the Heat map, there was a very high correlation among independent features which means high multicollinearity in our model. Due to the fact that each column is equally crucial for prediction, we are not deleting any columns.
After this I have divided our dataset into train and test data splitted into 80-20. Then, i have fitted my dataset into various models like Linear regression, Lasso regression, Ridge regression . And after analyzing the result from these regression model. The perfect fit model for this dataset is a Linear Regression.

