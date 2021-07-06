# Neural_Network_Charity_Analysis

## Overview
The purpose of this analysis is to help create a binary classifier that is capable of predicting whether applicatns will be successful if funded by Alphabet Soup. With a dataset that contains over 34,000 organizations that have received funding from Alphabet Soup over the years, a neural network model is compiled, trained, and evaluated. After that, 3 attempts were made to see if the data or model could be optimized such that it can result in over 75% predictive accuracy.

## Results
Target variable: IS_SUCCESSFUL
Features variable: Columns other than 'IS_SUCCESSFUL'
Removed variable: 'EIN' and 'NAME'

Without optimization:
Hidden layers: 2
Neurons: 12 for 1st, 8 for 2nd
Activation function (hidden layer): Relu
Activation function (output layer): Sigmoid

Result:

![]()

1st attempt:
Modification:

Hidden layers: 2
Neurons: 12 for 1st, 8 for 2nd
Activation function (hidden layer): Relu
Activation function (output layer): Sigmoid

Result:

![]()

2nd attempt:
Modification:

Hidden layers: 2
Neurons: 12 for 1st, 8 for 2nd
Activation function (hidden layer): Tanh
Activation function (output layer): Sigmoid

Result:

![]()

3rd attempt:
Modification:

Hidden layers: 8
Neurons: 12 for all hidden layers
Activation function (hidden layer): Relu
Activation function (output layer): Sigmoid

Result:

![]()

## Summary
