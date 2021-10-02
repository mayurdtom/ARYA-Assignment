# Assignment---Binary-Classification
Asisgnment Data Scientist    

**overview:**
For this Dataset, I built the model using Random Forest Classifier Algorithm. Done the Exploratory Analysis, Preprocessing, Feature Selection before building the model. After which I decided to build the model using Random Forest Cassifier as it was giving good performance based on the all performance matrices like accuracy, true positive ratio (tpr), false positive ratio (fpr), precision, F1 Ratio, ROC AUC Curve.

**Steps followed in the code**
## 1) Exploratory Analysis and Preprocessing: 
a) Removing Unwanted Columns
b) Checking for Nulls
c) Data Type Check
d) Class Imbalance Check - Checking the Distribution of Y (Target) variable
e) Check for Constant Columns (columns with singularities) and removing them.
   Using sklearn Variance Threshold 

## 2) Feature Selection:
   Feature Selection using Random Forest Feature Importance

## 3) Plotting the Feature Importances
   Top five features are : X52, X55, X21, X16, X56

## 4) Splitting Training dataset in the train and validation dataset

## 5) Model Building
   Uisng **Random Forest Classifier**
Based on the performance matrices:
1) Got good confusion matrix : [[455,  26],
                                [ 26, 275]]
2) High Accuracy Score : 93.35038363171356 %
3) High True Positive Ratio (TPR) : 0.9136212624584718
4) Low Fasle Positive Ratio (FPR) : 0.05405405405405406
5) High Precision : 0.9136212624584718
6) High F1 Ratio : 0.9136212624584718
7) High ROC AUC : 0.9297836042022088
Because of the Good Performance, done prediction using Random Forest Classifier

## 6) Model Predictions on Test Data

## Python Version : 3.8.5

## Libraries used:
1) Pandas  Version : 1.2.3
2) Numpy  Version : 1.19.2
3) Matplotlib  Version :3.3.2
4) Sklearn Version : 0.24.2
