# Melbourne_Housing_Regression
Regression Analysis


# Problem Description
Melbourne is currently experiencing a housing bubble (some experts say it may burst soon). Maybe someone can find a trend or give a prediction? Which suburbs are the best to buy in? Which ones value for money? Where's the expensive side of town? And more importantly, where should I buy a 2 bedroom unit?

# Software and Libraries Used
- Language: Python 
- Software: Jupyter Notebook
- Libraries: Pandas, Numpy, Matplotlib, Sklearn, Seaborn

Various Stages involved in this process are:
## 1. Data Cleaning
1. Removing Columns with more missing values as the dataset will be corrupted if the we replace the missing values.
2.  Dropping necessary columns like longitudes and latitudes.
3. Replacing the Missing values with less than 10% missing with mean
4. Formatting date, month, and year.
5. Converting Categorical Data into numerical data using label encoder.

# 2. Data Modelling
1. Splitting the data into train and test datasets using Sklearn packages 
2. Building General models of regression:
    1. KNN Regressor
    2. Linear Regressor
    3. Ridge 
    4. Lasso
    5. Polynomial Model
    6. linear SVM
    7. Kernel SVM
    8. Decision Tree
3. Applying the Bagging method to the following models:
    1. Lasso Regression
    2. KNN Regression
4. Applying the Pasting method to the following models:
    1. Lasso
    2. KNN Regressor
5. Applying the Adaboosting to the following models:
    1. KNN Regressor
    2. Lasso Regressor
6. Applied PCA to the data set and built the following models
    1. KNN Regressor
    2. Linear Regressor
    3. Ridge 
    4. Lasso
    5. Polynomial Model
    6. linear SVM
    7. Kernel SVM
    8. Decision Tree
7. Deep Learning Model
** Performed grid search for tuning the hyperparameters and cross-validation for assessing the effectiveness of each of the above models. 

## 3. Model Selection 
- the Model with the best R2 values is selected.



