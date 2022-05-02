# Shinkansen-Travel-Experience-Binary-Classification
The goal of the problem is to predict whether a passenger was satisfied or not considering his/her overall experience of traveling on the Shinkansen Bullet Train

Model: Random Forest with Cross-Validation

EDA + Data Preparation.

Merging Train and Test Data.
Correlation analysis.
Removing outliers from train data.
Removing rows for features with a little number of missing data.
Imputing missing data: 1. For highly correlated features - use the values of the corresponding highly correlated feature (correlation coefficient = 0.98). 2. For others: KNNImputer.
Encoding Categorical Values (binary and ordinary).
Removing high correlated features.
Feature engineering.
