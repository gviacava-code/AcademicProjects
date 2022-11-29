# Pima Indians Diabetes Analysis

## 1. Problem Statement

Analyze different aspects of Diabetes in the Pima Indians tribe by doing Exploratory Data Analysis

## 2. Data Description

Research was done on a tribe in America which is called the Pima tribe (also known as the Pima Indians). In this tribe, it was found that the ladies are prone to diabetes very early. Several constraints were placed on the selection of these instances from a larger database. All patients were females at least 21 years old of Pima Indian heritage. 

* Number of observations  - 768
* Number of variables/columns - 9 (all numeric interger values )
* nulls - 0

## 3. Modelling Algorithms

  - a. K-Nearest Neighbords Classifier
  - b. Linear Support Vector Machine Classifier
  - c. Random Forest Classifier
  - d. Decision Tree Classifier

*Metrics* - As the target variable is categorical, accurracy_score, f1_socre, precision_socre, and recall_score were used.

## 4. Results

**Model Decision Tree Classifier (dct) performs ok** with this dataset. Performance metrics are:

* Train data set ->  Accuracy: 0.814   |   F1 score: 0.749    |    Precision: 0.708    |   Recall: 0.794
* Test data set  ->  Accuracy: 0.779   |   F1 score: 0.691    |    Precision: 0.679    |   Recall: 0.704
* Cross Validation Accuracy: 0.716 (+/- 0.030) [DecisionTreeClassifier]

This *Accuracy* factor shows the model is able to predict 72% of observations. A Precision and Recall of also 70 aprox., indicate this model is correctly classifying labels at a good ratio.

**Predictors Glucose, BMI, and Age** are the most significant variables to predict Diabetes given this set of values.

Find below some charts to ilustrate de results:

a. Decision Tree 
b. Confusion Matrix
c. Feature Importance

![Summary Charts](https://github.com/giomvp/AcademicProjects/blob/72ce0121c2dad1dba1d4c21e33062bff88053a3a/PimaIndiansDiabetesAnalysis/imgs/summary_plt.jpg)

Complete model selection analysis [here](https://github.com/giomvp/AcademicProjects/blob/877ca09c742d1270f64592f27257f775e453c057/PimaIndiansDiabetesAnalysis/PimaIndiansDiabetesAnalysis.ipynb).
