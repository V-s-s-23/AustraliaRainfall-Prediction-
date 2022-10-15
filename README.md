# Australia-Rainfall-Prediction
Build a Artificial neural network with the Accuracy and F1-score of 88 and 93 percent.

# About Dataset:-
This dataset contains about 10 years of daily weather observations from many locations across Australia.

RainTomorrow is the target variable to predict. It means -- did it rain the next day, Yes or No? This column is Yes if the rain for that day was 1mm or more.

## Dataset Link:- https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package

## Challenges faced while creating the ANN:- Muliticollinearity, Outliers, and imbalanced data.
## But to deal with those problems, I used IQR(interquartile range) to deal with outliers and to deal with multicollinearity find Correlation, and make some new features.

# Following steps are included in making of ANN Model-
1. Data collection

2. Data Exploration

3. Data cleaning

4. Data prepration

5. Model Building

# Accuracy Measurses:- Used F-1 Score, precision score and accuracy score because data is imbalanced that's why using only accuracy score is not sufficient.
