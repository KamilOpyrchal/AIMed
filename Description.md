# Project: Cardiomegaly Prediction Model #
## Main Objective ##
The main task of this project is to create a Machine Learning Model that predicts if a patient has Cardiomegaly or not, based on given data.

## The Plan ##
1. Data Preparation
First, we want to normalize and scale our data. After processing, we will split it into a train and test set.

2. Baseline Model Selection
Secondly, we want to check which ML Model gives us the best results for predicting the illness. We will do this by using cross_val_score on several Machine Learning Models using their default settings and check which one performs best.

3. Tuning and Final Testing
Thirdly, we will use GridSearchCV to find the best hyperparameters for our selected ML Model. Finally, we will test this optimized model on our test set.