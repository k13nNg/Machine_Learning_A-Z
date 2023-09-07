# Machine_Learning_A-Z_Learning_Code

## Regression Summative Project

Data is retrieved from: https://www.kaggle.com/datasets/fedesoriano/the-boston-houseprice-data

$R^2$ score for different regression models:
  - Decision Tree Regression: -0.09937831917148121
  - Multiple Linear Regression: 0.6506243222334223
  - Multivariate Polynomial Linear Regression: -0.014402932695452897
  - Support Vector Regression: -6.05336504887059
  - Random Forest Regression (with 10 decision trees depth): 0.8031665803048987

It is obvious that the Random Forest Regression model out-performed the other models with an $R^2$ score of approximately 80%. This implies that approximately 80% of the dependent variable is explained by the independent variable

## Classification Summative Project

Data is retrieved from: https://www.kaggle.com/datasets/prathamtripathi/drug-classification

Accuracy score for different classification models:
- Decision Tree Classification: 0.9666666666666667
- K-Nearest Neighbours: 0.7333333333333333
- Kernel SVM: 0.9
- Logistic Regression: 0.9333333333333333
- Naive Bayes: 0.68333333333333330
- Support Vector Machine: 0.9
- Random Forest Classification: 0.9833333333333333

As classification problem is completely different from regression, where we do not need to predict the next data point based on the information learned from previous datapoints, $R^2$ scores would not be an accurate indicator of the model performance. 

Hence, we are going to use the accuracy_score metric offered by sklearn, which would be a more accurate measurement. 

From the list shown above, it is obvious that Decision Tree Classfication, K-Nearest Neighbours and Random Forest outperformed other classfication models, with the accuracy scores of 0.9666666666666667, 0.9333333333333333 and 0.9833333333333333. Out of the three, Random Forest Classfication appears to be the most accurate model, with an accuracy score of 0.9833333333333333. This implies that approximately 98% of the model's prediction is correct, which is extremely impressive. 
