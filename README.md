# Spam-Detection-Model-

The goal is to determine whether or not a message is spam or not. 
The dataset source is from https://static.bc-edx.com/mbc/ai/m4/datasets/spam-data.csv.

We use the following the models: Logistic Regression and Random Forest Classifier.
Before we begin we found that 

0:    2788

1:    1813

Name: spam, dtype: int64

The dataset is uneven and this will be an issue for logistic regression.

Logistic Regression

Calculate the accuracy score by evaluating `y_test` vs. `testing_predictions`.
accuracy_score(y_test, testing_predections)
0.9278887923544744

Random Forest Classifier
Calculate the accuracy score by evaluating `y_test` vs. `testing_predictions`.
accuracy_score(y_test, rf_predictions
0.9669852302345786

Both Logistic Regression and Random Forest Classifier performed well
for determining whether or not a message was spam. 
However the Random Forest Classifer performed better because dataset uneven as shown above.
