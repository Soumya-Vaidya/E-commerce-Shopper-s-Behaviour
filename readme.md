
# E-Commerce Customer Behavior Analysis and Purchase Prediction

Python-based solution for analyzing user behavior and predicting purchasing patterns in an e-commerce environment. The primary objective is to forecast whether a user will make a purchase based on diverse attributes collected throughout the year. 

## Contents

### Data Preprocessing 
#### Scikit-learn Pipeline:

Leveraged the Scikit-learn Pipeline for streamlined and efficient data processing.

#### Column Transformer:

Applied a ColumnTransformer to handle different types of transformations on various columns, such as OrdinalEncoder for ordinal variables and OneHotEncoder for categorical variables.

#### Simple Imputer:
Employed SimpleImputer to handle missing values in the dataset.

#### Categorical Variable Encoding:

Applied One-Hot Encoding to handle categorical variables efficiently.

#### Standard Scaler:
Utilized StandardScaler to standardize numerical features, ensuring they are on the same scale for machine learning models.

#### Handling Class Imbalance:

Addressed the issue of class imbalance using the Synthetic Minority Over-sampling Technique (SMOTE).

### Model Selection and Training
Employed various machine learning models for purchase prediction.
- Logistic Regression
- Ridge Classifier
- K-Neighbors Classifier
- SVC
- Decision Tree Classifier
- Extra Trees Classifier
- Random Forest Classifier
- AdaBoost Classifier
- Gaussian NB
- SGD Classifier

### Hyperparameter Tuning and Evaluation:

- Conducted hyperparameter tuning using Grid-search Cross-Validation for optimal model configuration.
- Evaluated and compared model performance using various metrics such as F1 score.