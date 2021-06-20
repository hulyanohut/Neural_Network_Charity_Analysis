# Neural_Network_Charity_Analysis

- To assist a non-profit in predicting where to invest, use machine learning and neural networks.

# Overview

The goal of this study was to use a neural network to assist a non-profit in identifying investment options for fundraising.

This project compromised of the following 3 steps:

 - Preprocessing the data for the neural network

 - Compile, Train and Evaluate the Model

 - Optimizing the model

# Results

# Data Preprocessing

- Variable that was considered as the target for my model: IS_SUCCESSFUL Column

- Variables that were considered features for my model: Every Column except for IS_SUCCESSFUL which is our target and the ones we will drop

Feature variables for the model:

  APPLICATION_TYPE
    
  AFFILIATION
    
  CLASSIFICATION
    
  USE_CASE
    
  ORGANIZATION
    
  STATUS
    
  INCOME_AMT
    
  SPECIAL_CONSIDERATIONS
    
  ASK_AMT
    
Removed variables from the input data:

  EIN
    
  NAME
    
# Compiling, Training, and Evaluating the Model

- Neurons, layers, and activation functions

layer1 = 80 with activation= relu

layer2 = 30 with activation= relu 

Outer layer activation =  sigmoid

 - Were you able to achieve the target model performance?

268/268 - 0s - loss: 0.5602 - accuracy: 0.7275

Loss: 0.5601833462715149, Accuracy: 0.7274635434150696

What steps were taken to try and increase model performance?

- Adding hidden layers, adjusting the activation type, changing the number of epochs, and modifying the number of neurons in each layer were some of the measures I did to improve the model's accuracy.


# Summary

- We might utilize a supervised machine learning model like the Random Forest Classifier to mix a number of decision trees to get a categorized output and compare its performance to our deep learning model because we are in a binary classification situation.

- The model appears to have reached its maximum at 73 percent accuracy, with minimal optimization efforts improving the model's ability to determine whether an application was successful.

- Random Forest may be a good model for solving the classification problem,because the data contains numerous categorical variables
