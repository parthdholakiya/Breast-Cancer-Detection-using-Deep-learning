# Breast-Cancer-Detection-using-Deep-learning

## Overview
This project aims to predict whether a mammogram mass is benign or malignant using deep learning. The dataset used is the "mammographic masses" public dataset from the UCI repository, which contains 961 instances of masses detected in mammograms, with attributes such as patient age, mass shape, margin, density, and severity (benign or malignant).

## Dataset
#### BI-RADS assessment: 1 to 5 (ordinal)
#### Age: patient's age in years (integer)
#### Shape: mass shape: round=1 oval=2 lobular=3 irregular=4 (nominal)
#### Margin: mass margin: circumscribed=1 microlobulated=2 obscured=3 ill-defined=4 spiculated=5 (nominal)
#### Density: mass density high=1 iso=2 low=3 fat-containing=4 (ordinal)
#### Severity: benign=0 or malignant=1 (binominal)

## Objectives
Build a deep learning model to predict the severity (benign or malignant) of mammogram masses.
Use feature engineering and normalization to prepare the data.
Utilize the scikit-learn library for model building and evaluation.
## Usage
-Import the dataset into a Pandas dataframe.
-Evaluate the data to understand its characteristics and handle missing values.
-Convert the Pandas dataframes into numpy arrays for use with scikit-learn.
-Normalize the attribute data for models that require it.
-Set up a multi-layer perceptron (MLP) model using Keras.
-Wrap the Keras model in an estimator compatible with scikit-learn.
-Use cross-validation to evaluate the model's performance.

## Conclusion
Predicting the severity of mammogram masses is crucial for identifying potential cases of breast cancer. By building a deep learning model on this dataset, we can contribute to improving the accuracy of mammogram interpretations and reduce unnecessary surgeries and patient anxiety resulting from false positives.
