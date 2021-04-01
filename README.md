# ml-stroke

Test ML models to predict stroke from clinical data
The dataset is imbalanced (only 5% positive for stroke) and has null values
The goal was to try to balance the F1 scores given that the imbalance makes for a very poor prediction of the stroke cases

1. Data analysis: overview of data
2. Data cleansing: drop unnecessary columns, input NaN values
3. Encoding (label/one-hot)
4. Split of the set: scaled with StandardScaler, oversampled with SMOTE
5. Test models:
 - SVM
 - Logistic Regression
 - Gaussian Naive Bayes
 - Decision Tree with Grid Search
 - Random Forest
 - XGB 
 - Balanced Random Forest
