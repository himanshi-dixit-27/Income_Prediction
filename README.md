# Income_Prediction
This is a Machine Learning Project(Exploratory Data Analysis and Data Mining)

This Project revolves around predicting income values through adult-income dataset.It includes 15 columns out of which 14 are features 
and 1 is the label.The features include ['AGE','WORKCLASS','FINAL-WEIGHT','EDUCATION','EDUCATION-DEGREES','MARITAL_STATUS','OCCUPATION',
'RELATIONSHIP','RACE','GENDER','CAPITAL-GAIN','CAPITAL-LOSS','HOURS-PER-WEEK','COUNTRY','GROSS-INCOME'] while the label for prediction
includes [GROSS-INCOME] which is either classified as '<=50k' or'>50k'.The dataset also includes missing values which are replaced by the 
mode(most frequently occuring value) of that particular column.Out of 14 features 8 are of Categorical data type.Such columns are encoded into 
numbers using 'Label Encoder'.I have used XGB Classifier because it has parameters like n_estimators,learning rate,early_stopping_rounds 
which makes our model more precise and accurate.I have used Matplotlib to plot importance of each feature in prediction model.This gives us an
an insight of how the number of features affect the accuracy of prediction of data.Greater the number of features,greater is the accuracy of our
model.
