# **Neural Network Charity Analysis**

## **Overview:**

The purpose of this analysis is to help the Alphabet Soup foundation predict where to make investments, using machine learning and neural networks to create a binary classifier that is capable of predicting whether applicants will be successful if funded.

## **Results:**

### *Data Preprocessing*

- "Is Successful" is the target variable for the model.
- The following variables are the features for the model: "Status", "Ask Amount", "Application Type", "Income Amount", and "Special Considerations."
- The following variable(s) are neither targets nor features, and were removed from the input data: "EIN" and "Name."

### *Compiling, Training, and Evaluating the Model*

- I tried 120 neurons, three layers, and the tanh and ReLu activation functions for my neural network model to try to increase the accuracy score of 0.75 or greater.
- My three attempts were unable to meet the target model performance of an accuracy score of 0.75 or greater.
- I took the following steps to try and increase model performance: 1) use different activation functions 2) add a hidden layer and 3) remove more input data.

## **Summary:** 

Unfortunately, the highest accuracy score of my three attempts was 0.726 so none of attempts were successful. I recommend trying a random forest model for this dataset, since this type of classifier can easily handle outliers and nonlinear data.
