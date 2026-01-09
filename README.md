
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

# accuracy metrics
from sklearn import metrics
from sklearn.model_selection import cross_val_score, cross_validate, GridSearchCV
from sklearn.metrics import accuracy_score, ConfusionMatrixDisplay, confusion_matrix, classification_report, roc_curve, precision_score, recall_score, roc_auc_score
