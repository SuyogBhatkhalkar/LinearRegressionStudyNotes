# LinearRegressionStudyNotes
This project demos linear regression technique to predict file delays. It has below files
In This study notes we can learn below: 
1. FlightDelayPredictionDataIngestionTransformation.ipynb: This notebook ingest data from different csv files downloaded from Kaggle. It install pySpark to transform the data as required.  It merges three csv files into one, convert datetime , remove nulls and filter data based on one ariline.
2. FlightDelayPredictionFeatureSelection.ipynb:  Based on Data ingested and transformed from the previous notebook, this notebooks create different views on the data, detects outliers,  plot co-releation and drops highly correlated column
3. FlightDelayPredictionModel.ipynb : This file predict the flight delays based on linear regression, it also test efficiency of the model by plotting various errors, and then do L1 (Lasso ) and L2 (Ridge) regression using sklearn libaraires. 
4. GradeintDescentLinearRegression.ipynb : Plot gradient descent , cost function to tune the model further.

The data sets are taken from kaggle: 
https://www.kaggle.com/usdot/flight-delays
