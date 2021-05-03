# assignments



The Data is highly non stationary and to include other features such as fuel price temprature a good way to start would be including time based features in machine learning model.


The Sales show some trends based on the corrosponding departments.


Also the sales also shows yearly trend. So to include last year weighted ssales as feature will seems to be intutive.


For imputation of annomysed features we can use simple interpoaltion because it is hard to interpret what they mean. For imputing last year sales I've used Knn_Imputatio.

For base line model i've used simple linear regression. Which gave R^2 of 0.902 on test and 0.903 on train which is really good. but it was'nt able to predict the peaks during special days.
So for it I've usssed Xgboost model.

which gave r2 on 0.96 and was able to predict the peaks


## Further improvements
I think I can include other features such as roling mean, lag2, lag1, based on Aic values. also the average sales last year for corrosponding month.
