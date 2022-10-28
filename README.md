# Neural-Network-Charity-Analysis


## Overview
* Using the features in the provided dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results:

#### Data Preprocessing
* The target variable our neural network is intended to predict as accurately as possible is the “IS SUCCESSFUL” column of our dataset

* The variables we consider to be features are the “APPLICATION_TYPE” column as well as the “CLASSIFICATION” column.
* Looking at our DataFrame we can infer that the “EIN” and the “NAME” columns provide no statistical value to our analysis.

#### Compiling, Training, and Evaluating the Model
* For the neurons after following the general rule of thumb we used 2 to 3 times the neurons to our inputs. 3 hidden layers and 4 activation functions counting the output activation functions.

* After the optimization we were able to find 74% accuracy in our model.
* It took countless times fine tuning the model in order to achieve the best possible accuracy

## Summary:
* In summary after adding additional hidden layers and neurons our accuracy improved by over 20%
