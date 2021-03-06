# Fetal-Heart-Conditon-diagnosis
# Project Task 1
 A classification example: fetal heart condition diagnosis
We have a data set of fetal heart diagnosis containing measurements from about 2,600 fetuses. This is a classification task, where our task is to predict a diagnosis type following the FIGO Intrapartum Fetal Monitoring Guidelines: normal, suspicious, or pathological.


There are some steps to do this project:
* Reading the data
* Training the baseline classifier
* Trying out some different classifiers
* Final evaluation


# Project Task 2
Decision trees for classification
Use the defined class TreeClassifier as your classifier in an experiment similar to those in Task 1. Tune the hyperparameter max_depth to get the best cross-validation performance, and then evaluate the classifier on the test set. Also, mention what value of selected and what accuracy you got.


# Project Task 3
A regression example: predicting apartment prices
Here is another dataset. This dataset was created by Sberbank and contains some statistics from the Russian real estate market. Here is the Kaggle page where you can find the original data.
Since we will just be able to handle numerical features and not symbolic ones, we'll need a simplified version of the dataset. So we'll just select 9 of the columns in the dataset. 
The goal is to predict the price of an apartment, given numerical information such as the number of rooms, the size of the apartment in square meters, the floor, etc. Our approach will be similar to what we did in the classification example: load the data, find a suitable model using cross-validation over the training set, and finally, evaluate the held-out test data.
* Apply some possible regression models 
* Train on the full training set and evaluate on the held-out test set:
