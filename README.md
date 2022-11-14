# ML-Project_1-Breast_cancer_detection
### Data Details 

  Kaggle - https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data  
  Colab Notebook - https://colab.research.google.com/drive/1vHDv-iy9IYULRWSe9M6aM_XE_xV1dYcL?usp=sharing  
  
#### Please use the Ipynb file in the repository for a detailed explanation of this project. This is because the project has been completed and the steps have been written in the notebook referenced in the repository.
Link - https://github.com/SudeepSinha09/ML-Project_1-Breast_cancer_detection/blob/main/Breast_cancer_detection_analysis.ipynb

## project brief

As part of this project, I cleaned the data, after which I train-tested the data, and then I made models using the train data.

For the given situation, there are three possible models, namely (i) Logistic regression (ii) Random Forest (iii) XGBoost

In order to determine the accuracy of each model, I made predictions based on the train data before making the models, i.e. predicting the models with the train data.

Using these parameters, we found that the accuracy, recall, precision, and f1 scores of both logistic regression models and random forest models or XGBoost models are approximately the same, so we cannot predict the best model based on these parameters.

so now we are checking for the Cross Validation test

Result - from cross-validation test we found that the Logistic regression model is more accurate as compared to the Random forest model and XGBoost model

##### The model selected - Logistic regression
