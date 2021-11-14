# Neural_Network_Charity_Analysis

## Overview
The purpose of this challenge was to create a deep learning model to determine if applicants will be successful if funded by Alphabet Soup.

## Results

### Data Preprocessing
What variables are considered the targets for the model?
* Target was the IS_SUCCESSFUL column which determined if the money was used effectively.

What variables are considered to be features?
* App type, affiliation, classification, use_case, organization, status, income status, special considerations, ask amount

What variables are neither targets nor features?
* EIN and NAME identification columns

### Compiling, Training, # Evaluating Model
How many neurons, layers, and activation functions were used?

* 75 nodes were used in first hidden layer, 25 nodes were used in the second hidden layer.
* Two hidden layers were used initially
* Two different activation functions were used, one for the hidden layers and another for the output.

Was target accuracy achieved?

* Initially accuracy was at 70%, which was just below target accuracy of 75%. Subsequent attempts did not achieve target accuracy
What steps were taken to try and increase accuracy?
* Method 1 - Hidden layer activation functions were updated
* Method 2 - Output activation function was updated
* Method 3 - Number of nodes was increased for each hidden layer
* Method 4 - Additional hidden layer was added and number of epochs was increased

## Summary
The highest accuracy was achieved with the first iteration of the model at 70%. Subsequent attempt results were added to the results folder in the repository, however none of the four attempts were able to improve on the 70% accuracy rate.

I would recommend using a random forest model as this model is flexible for both classification and regression, works well with both categorical and continuous values, and reduces the likelihood of overfitting and can help improve accuracy.
