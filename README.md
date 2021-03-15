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
As a result, the highest target model performance was 72.35%. Three attemots were completed to get closer to the accurancy of 75%. The first attempt used three hidden layers combined with "relu" and "sigmoid" activation, which led an accuracy of 72.22%. The second attempt used four hidden layers combine with "relu" and "sigmoid" activation type to get to an accurancy of 72.15%. The third attept used three hidden layers combined with "ranh" and "sigmoid" activation type, which led to the highest accuracy amoung the three 72.35%. 
