# Titanic-Survival-prediction-from-Kaggle
analysis of what sorts of people were likely to survive. In particular, we ask you to apply the tools of machine learning to predict which passengers survived the tragedy.

The step one is to provide data analysis and prepare the data for data modeling from data anamolies
STEP 1 - Data preparation consists of step to prepare the data for modeling
STEP 2 - Modeling for final preparation using Logistic regression consists of data modeling technique for prediction of survival of titanic passengers
Train.csv -> Source training file which has missing age values 
test.csv -> Source testing file which has missing age values
%=======================================================source cleaning and prediction for training===============================

TrainWithAgeValues.csv -> Source cleaned training file which has correct age values for training to predict the missing age values
TrainWithoutAgeValues.csv ->source cleaned testing file to predict the age values from above training file

TrainAgeValuesCalculated.csv ->predicted age values of the training file
FinalTraining.csv ->Final Training file that contains the sorce cleaned training file with proper age values and predicted age values
%=======================================================source cleaning and prediction for testing===============================

TestingfileWithAge.csv -> Source cleaned testing file which has correct age values for training to predict the missing age values
TestFileWithoutAge.csv ->source cleaned testing file to predict the age values from above testing file

TestingAgeValuesCalculated.csv ->predicted age values of the testing file
FinalTestingFile.csv ->Final Training file that contains the sorce cleaned training file with proper age values and predicted age values
%==========================================================================================================================
FinalTraining.csv is converted to MainMatlBtraining.txt and loaded into matlab for training
FinalTesting.csv is converted to FinalTestingFile.txt and loaded into matlab for training
