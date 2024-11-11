# Deep learning challenge


## Overview 
This analisys is to predict whether applicants will be successful if funded by Alphabet Soup.
Into the provided dataset there are the next data.
EIN and NAME—Identification columns
APPLICATION_TYPE—Alphabet Soup application type
AFFILIATION—Affiliated sector of industry
CLASSIFICATION—Government organization classification
USE_CASE—Use case for funding
ORGANIZATION—Organization type
STATUS—Active status
INCOME_AMT—Income classification
SPECIAL_CONSIDERATIONS—Special considerations for application
ASK_AMT—Funding amount requested
IS_SUCCESSFUL—Was the money used effectively


With this set of data we must select which data can help us with this purpose


## Results

### Data Preprocessing

What variable(s) are the target(s) for your model? 
 IS_SUCCESSFUL

What variable(s) are the features for your model?
 APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION,INCOME_AMT

What variable(s) should be removed from the input data because they are neither targets nor features?
 EIN, NAME, STATUS, SPECIAL_CONSIDERATIONS, ASK_AMT

### Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
I used 8 hidden_nodes_layer1 and 5 hidden_nodes_layer2 taking it to 20 to find the target of 75% I used "relu" because I considered it was convenient to improve the response speed.

Were you able to achieve the target model performance?
I was unable to achieve the precision target.

What steps did you take in your attempts to increase model performance?
I removed columns, added more layers, additional hidden nodes and changed some activation functions.


## Summary

With the selected elements the model had an accuracy of around 73%. It is necessary to feed a previous correlation to improve the accuracy of the model.

Using Random Forest can offer a more interpretable and robust alternative to deep neural networks, especially when working with structured data. However, the choice of model ultimately depends on the specific characteristics of your data and the problem you are trying to solve.
