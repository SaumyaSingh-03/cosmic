# cosmic
Steps before training the model on data set
1. handling missing values - we found the mean value of all 10 categories and put those mean values in place of missing values.
2. Hnadling outliers - checked outliers box plot then used clipping technique for outliers.

after all these there were some missing values we dropped them
We trained xgboost model 
We selected this model because it gave more accuracy than other ML models

And we used some specific parameters whoch we find from Grid Search.

And then at end we trained the model
