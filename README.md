# Seoul-Bike-Sharing-Demand-Prediction

Prediction was using Datafile name SoeulBikeSharing.CSV file of 600KB file consists of 14columns and 8670rows.

Bike sharing systems are a means of renting bicycles where the process of renting bike on the hourly basis is given in this dataset. 
Certain features will play a major role on Bike Count so by taking care of that we have to make a model that can predict Rental Bike Count by using the independent features present in the dataset.


## Presentation

[Here is the presentation link](https://github.com/saransh2396/Seoul-Bike-Sharing-Demand-Prediction/blob/main/Bike%20Count%20%20Project%20PPT.pdf)

# Summary
Starting with loading dataset, treating null values, EDA, Transformation of data, handling skewness in data, Removing Outliers, Removing Multicollinearity, Label Encoding, Feature Engineering and then selecting the features we have implemented three models and our r2 score varies from 56.6% to 87% among all the models used. We have to use Ensemble Techniques as our model was underfitted even after applying hyperparameter tuning. As bagging technique like Random Forest Regression is prone to overfitting, we optimized it by again using Hyperparameter tuning on it.
