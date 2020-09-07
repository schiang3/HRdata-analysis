# HRdata-analysis
IBM HR Analytics Employee Attrition & Performance dataset is found on Kaggle and it is a classification
problem. The target is Attrition. There are 34 features in the original dataset. After encoding the
categorical features and cleaning the dataset, the dataset is 1470 rows and 51 features. The
target is Attrition, and the goal is to gather the important features in employees who are likely to
leave their job. 237 out of 1470 employees leaves their job, which is around 16% of all cases. It
is a challenge to make predictions without demonstrating resample mothed such as
oversampling, SMOTE and SMOTEENN, and undersampling on the training set. Conducting
feature selections by embedded techniques, for example, Gradient boosting and Random
Forest can reduce the model’s complexity.

This research is focused on comparing different approaches in resampling methods, feature
selections, the prediction of attrition by performing Gradient boosting, Random Forest, Ada
Boosting, Decision Trees, and Support Vector Machine machine learning algorisms on this
dataset. The model performance will be evaluated by the classification report which is included
accuracy, AUC, precision, recall, F1-score, and support. Since this dataset has a serious
imbalanced class issue, the AUC score and F1-score will take more accountability in the
evaluation. Besides training and test set split, the cross-validation will be utilized in this research
as well. The goal is to explain common features from the models that have high AUC, high
F1-score, and low run-time. Additionally, visualizing the top 15 importance features from the
models and compare the ranks of feature importance in different machine learning methods.
