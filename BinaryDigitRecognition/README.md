# Binary Handwritten Digit Recognition

See complete model selection and analysis [here](https://github.com/giomvp/AcademicProjects/blob/d5ac7371ee69286f91de43ad8e50921057fdcf26/BinaryDigitRecognition/BinaryDigitRecognition.ipynb).


## 1. Problem Statement

Use a neural network to recognize the hand-written digits zero and one. This is a binary classification task.

## 2. Data Description

The data set contains 8817 training examples of handwritten digits, limited to zero and one. Each training example is a 28-pixel x 28-pixel grayscale image of the digit. 

* Number of observations  - 8817
* Number of variables/columns - 784 (all numeric values)
* Column 1 is the target value (lebel)

## 3. Modelling Algorithms

Tensorflow - Keras (api): 

  * Model: Sequential - Dense
  * Loss: BinaryCrossentropy
  * Optimizer: Adam

* Metric - As the target variable is categorical, accurracy_score, f1_socre, precision_socre, and recall_score were used.

