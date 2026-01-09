
This repository provides a machine learning model trained on the ACME Happiness Survey dataset from Apziva. The model’s goal is to predict customer satisfaction directly from survey responses.

# Prerequisites
To run the code, the following packages must be installed:
- pandas
- numpy
- matplotlib and seaborn
- scikit-learn
- seaborn

# models: Models that I will test to choose the best Model

from sklearn.model_selection import train_test_split
- LogisticRegression
- DecisionTreeClassifier
- RandomForestClassifier
- SVC
- KNeighborsClassifier
- GaussianNB


# Fitting and Evaluating the Models

We train several machine learning models and use Recall and AUC to decide which one works best. Recall is important because, in past fintech projects, low recall meant we missed many risky applicants, leading to financial losses. So, we want to reduce the number of such cases. AUC is also useful since it measures the overall strength of a model by checking its performance across different thresholds


# Feature Selection

Feature selection is the process of choosing only the most useful input features for a machine learning models. It helps improve model performance.


# Conclusions
Based on the clf_compare results, here are the models that have a Test Accuracy greater than 0.73:

- RandomForestClassifier

- KNeighborsClassifier

- XGBClassifier

- DecisionTreeClassifier

Among these, the XGBClassifier has the highest AUC1 of 0.83333, while also meeting the accuracy requirement of greater than 0.73. Therefore, the XGBClassifier is the best model based on these criteria.
