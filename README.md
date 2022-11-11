# Neural Network Charity Analysis

## Overview of the analysis: 

With my knowledge of machine learning and neural networks, I’ll use the features in the provided dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results: 

### Data Preprocessing

- The "IS_SUCCESSFUL" variable was considered to be the target for my model.
- 'APPLICATION_TYPE', 'AFFILIATION', 'CLASSIFICATION', 'USE_CASE', 'ORGANIZATION', 'INCOME_AMT' are considered to be 
  the features for your model.
- 'EIN','NAME', 'SPECIAL_CONSIDERATIONS' are neither targets nor features, and should be removed from the input data.
### Compiling, Training, and Evaluating the Model

- The initial model consisted of 110 neurons across 2 hidden layers with 80 neurons in the first layer and 30 in the second. I used relu activation functions for the hidden layers and sigmoid for the ouput layer
  as they are well suited to deal with classification.
- After three attempts I was unable to attain the target performance.
- In my first attempt at optimizing the model I added 10 nodes to each layer and the output was not significantly improved. I then added an additional hidden layer which also did not significantly improve the model performance.
  Finally, I changed the activation functions in the hidden layers to tanh. 

## Summary: 

In all because I was unable to achieve the target results with the current model and dataset I would recommend using a random forest model to see how that compares.