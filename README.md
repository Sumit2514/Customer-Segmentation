# Customer-Segmentation

# Introduction:

Two dataset was given i.e. train data and test data . In train dataset independent
variables contain lots of missing values and dependent variable is given. In test 
dataset dependent variable columncontain missing value and all other independent 
variables values are given.

# Objective:

Objective of this project was customer segmentation into three categories i.e.low, 
medium and high.

# Method:

First step was data cleaning was done . In data cleaning process,train data was 
divided into three categories i.e. low,medium and high . This project impute the 
missing values in low categories with most frequent value in that category. Repeat 
the same for medium and high segment. New data set is created by clubbing all 
segments.Split the data into train and test.XGBClassifier machine learning 
technique was used .

# Result:

Model achieve accuracy of 74.48% . This accuracy look fair enough .Futher create 
confusion matrix for accuracy . After observing the result , 
we are confident that model is predicting accurately.
