## Classification
[< supervised learning](../../Introduction.md)

Main objective of classification task is to identify the test data into specific and different classes. The classification tasks can be divided into several categories as stated below.[^1]

### Binary Classification
- Refer to task that involes with 2 class labels, such as true/false, 0/1
- Popular algorithm includes:
    - [Logistic Regression](Logistic-Regression/logisticRegression.md)
    - [Support Vector Machine](SVM/svm.md)   
    - [Decision Tree](Decision-Tree/decisionTree.md) 
    - [k-Nearest Neighbours](k-Nearest-Neighbours/k-NearestNeighbours.md)

### Multiclass Classification
- Refer to task that involes with more than 2 class labels
- Popular algorithm includes: 
    - [Logistic Regression](Logistic-Regression/logisticRegression.md)
    - [Support Vector Machine](SVM/svm.md)   
    - [k-Nearest Neighbours](k-Nearest-Neighbours/k-NearestNeighbours.md)
    - Naive Bayes
    - Random Forest
    - Gradient Boosting

### Multi-label Classification
- Refer to task that involes with 2 or more class labels, where 1 or more labels may be predicted
- Popular algorithm includes: 
    - Decision Tree
    - Random Forest
    - Gradient Boosting

### Imbalanced Classification
- When the dataset for each classes are not equally distributed
- Considered as binary classification, where the model focus minority class
- Popular algorithm includes: 
    - [Logistic Regression](Logistic-Regression/logisticRegression.md)
    - [Support Vector Machine](SVM/svm.md)   
    - [Decision Tree](Decision-Tree/decisionTree.md) 

<!-- ### DIfferent approaches of data classifications
| Class 1 | Class 2 |
|---|---|
| based on dichotomous distinction of classes | based on probability of y given that x |
| [SVM](SVM/svm.md) |  [Logistic regression](Logistic-Regression/logisticRegression.md)<br/> [k-nearest neighbours](k-Nearest-Neighbours/k-NearestNeighbours.md)<br/> [Decision tree](Decision-Tree/decisionTree.md)| -->

[^1]: Jason Brownlee. (2020, August 19). *4 Types of Classification Tasks in Machine Learning* https://machinelearningmastery.com/types-of-classification-in-machine-learning/