# INTRODUCTION

This notebook is an exercise from the Intermediate Machine Learning course on Kaggle.

In this exercise, I will train a model with gradient boosting.

## HOUSING PRICE PREDICTION WITH XGBOOST MACHINE LEARNING MODEL

If you ask a home buyer to describe their dream house, they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad.

But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing almost every aspect of residential homes in Ames, Iowa, this competition challenges data scientists to predict the final price of each home.

## GOAL

My job is to predict the sales price for each house. For each ID in the test set, my model will predict the value of the SalePrice variable.

## EVALUATION METRIC

The model is evaluated on the Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price. (Taking logs means that errors in predicting expensive houses and cheap houses will affect the result equally.)

## STEPS COVERED IN THIS NOTEBOOK

### Step 1: Build the model

**Part A**

In this step, I built and trained the first model with gradient boosting.

**Part B**

I set predictions_1 to the model's predictions for the validation data (validation features are stored in X_valid).

**Part C**

Finally, I used the mean_absolute_error() function to calculate the mean absolute error (MAE) corresponding to the predictions for the validation set (the validation data are stored in y_valid).

### Step 2: Improve the model

Now that the model has been trained on a default model as a baseline, it's time to tinker with the parameters, to see if I can get better performance!

### Step 3: Break the model

In this step, I tried to create a model that performed worse than the original model in Step 1. This helped me develop my intuition for how to set parameters. Maybe I'll even find that I accidentally get better performance, which is ultimately a nice problem to have and a valuable learning experience!

Dive in!
