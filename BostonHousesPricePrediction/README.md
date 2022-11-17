# Boston House Price Prediction

## 1. Problem Statement

The problem on hand is to predict the housing prices of a town or a suburb based on the features of the locality provided to us. In the process, we need to identify the most important features in the dataset. We need to employ techniques of data preprocessing and build a linear regression model that predicts the prices for us. 

## 2. Data Description

Each record in the database describes a Boston suburb or town. The data was drawn from the Boston Standard Metropolitan Statistical Area (SMSA) in 1970. Detailed attribute information can be found below.

* Number of instances  - 506
* Number of Attributes - 13 (12 inputs, 1 output)

## 3. Modelling Algorithms

Algorithms were selected following scikit-learn algorithm cheat-sheet

  * Ridge regression
  * SVR (linear)
  * SVR (rbf)
  * Xgbregressor
  * Random Forests

* Metric - Since the target variable is a continuous variable, regression evaluation metric RMSE (Root Mean Squared Error) and R2 Score (Coefficient of Determination) have been used.

## 4. Results

Random forest (rf) Shows good and consistent performance results as this model explains **84% (r2_score)** of the variability in the price through its independent variables and can make predictions within **~14% (mape)** of the price value on average.

Metrics:

  1. Train data set ->  r2_score: 0.91  |    mse: 7.15   |  rmse: 2.67  |   mae: 2.08 |   mape: 0.11
  2. test data set ->  r2_score: 0.84  |    mse: 13.93  |  rmse: 3.73  |   mae: 2.55 |   mape: 0.14
  3. Cross Validation Accurracy (r2_score): 0.84 (+/- 0.04)

![Summary Charts](https://github.com/giomvp/AcademicProjects/blob/5b36cf9a000eec3c52c64a75badea0b29f95c820/BostonHousesPricePrediction/img/summary_plt.jpg)
