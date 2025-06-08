# mlproject2
[Predict whether a customer continues with their account or closes it] (https://www.kaggle.com/competitions/playground-series-s4e1) 

logistic regression, random forest, LDA, QDA, XGBoost, and SVM models prediction accuracy was evaluated using ROC curve and submission score.

Code given by the professor was used to examine the characteristics of the data provided by Kaggle.

Using this code, categorical variables and numerical variables were distinguished. 

After reading the data, categorical variables were transformed into numerical variables using One-Hot Encoding.

The train_data was split into training and test sets in an 80:20 ratio.

The model was trained using the training set of the train_data, the accuracy of the prediction was evaluated with the test set, and a ROC graph was created.

All models were trained and evaluated equally. And the ROC graph was drawn in cumulative form.

In the case of SVM model, training time was very long compared to other models.

mlproject2.ipynb is a code that applies the above process without variable(feature) scaling.

mlporject2-scaled.ipynb is a code that applies the above process with variable(feature) scaling.
