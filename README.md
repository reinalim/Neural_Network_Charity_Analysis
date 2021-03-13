# Neural_Network_Charity_Analysis

## Overview

The purpose was to create a binary classifier that is capable of predicting whether applicants will be successful funded based on organizations that have received funding in the past.

## Result
### Data Processing

- The target variable is the is-successful column
- Features: NAME, APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT,SPECIAL_CONSIDERATIONS, and ASK_AMT
- Data Removed:EIN because its not important and it would throw things off, STATUS because the number never changed

### Compiling, Training, and Evaluating the Model
- There are 3 hidden layers and two to three different activation functions in the optimized model to increase the performance accurancy. 
- The target model performance was not able to achieved. Three attempts were completed to get closer to the accurancy of 75%.
- The following steps are taken to try to increase model performance: using a sigmoid function instead of relu for the activation in the second layer as well as the added 3rd layer, using data points for the names

## Summary
