# ML-Project_1-Breast_cancer_detection
### Data Details 

  Kaggle - https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data  
  Colab Notebook - https://colab.research.google.com/drive/1vHDv-iy9IYULRWSe9M6aM_XE_xV1dYcL?usp=sharing  
  
#### Please use the Ipynb file in the repository for a detailed explanation of this project. This is because the project has been completed and the steps have been written in the notebook referenced in the repository.
Link - https://github.com/SudeepSinha09/ML-Project_1-Breast_cancer_detection/blob/main/Breast_cancer_detection_analysis.ipynb

## Description

Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image.
n the 3-dimensional space is that described in: [K. P. Bennett and O. L. Mangasarian: "Robust Linear Programming Discrimination of Two Linearly Inseparable Sets", Optimization Methods and Software 1, 1992, 23-34].

This database is also available through the UW CS ftp server:
ftp ftp.cs.wisc.edu
cd math-prog/cpo-dataset/machine-learn/WDBC/

Also can be found on UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29

## An Overview of EDA

![image](https://user-images.githubusercontent.com/93086122/207615285-5533897a-fb0f-435b-a99a-ad85e651deb5.png)

![image](https://user-images.githubusercontent.com/93086122/207615586-3e00a40a-74d7-4b69-8e8c-576e636a94e3.png)


## Attribute Information

1) ID number
2) Diagnosis (M = malignant, B = benign)
3-32)

Ten real-valued features are computed for each cell nucleus:

a) radius (mean of distances from center to points on the perimeter)  
b) texture (standard deviation of gray-scale values)  
c) perimeter  
d) area  
e) smoothness (local variation in radius lengths)  
f) compactness (perimeter^2 / area - 1.0)  
g) concavity (severity of concave portions of the contour)  
h) concave points (number of concave portions of the contour)  
i) symmetry  
j) fractal dimension ("coastline approximation" - 1)  

The mean, standard error and "worst" or largest (mean of the three
largest values) of these features were computed for each image,
resulting in 30 features. For instance, field 3 is Mean Radius, field
13 is Radius SE, field 23 is Worst Radius.

All feature values are recoded with four significant digits.

Missing attribute values: none

Class distribution: 357 benign, 212 malignant


## Project Brief

As part of this project, I cleaned the data, after which I train-tested the data, and then I made models using the train data.

For the given situation, there are three possible models, namely (i) Logistic regression (ii) Random Forest (iii) XGBoost

In order to determine the accuracy of each model, I made predictions based on the train data before making the models, i.e. predicting the models with the train data.

Using these parameters, we found that the accuracy, recall, precision, and f1 scores of both logistic regression models and random forest models or XGBoost models are approximately the same, so we cannot predict the best model based on these parameters.

so now we are checking for the Cross Validation test

Result - from cross-validation test we found that the Logistic regression model is more accurate as compared to the Random forest model and XGBoost model

##### The model selected - Logistic regression
