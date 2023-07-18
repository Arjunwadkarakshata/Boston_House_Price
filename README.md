# Boston_House_Price

The goal of this project is to predict house price in boston city for users.
The CSV data is loaded with the help of read_csv method in pandas library.
The dataset consists of 506 samples and 14 features with 1 prediction feature.

# DATA SUMMARY:
1. CRIM             - per capita crime rate by town
2. ZN               - proportion of residential land zoned for lots over 25,000 sq.ft.
3. INDUS            - proportion of non-retail business acres per town.
4. CHAS             - Charles River dummy variable (1 if tract bounds river; 0 otherwise)
5. NOX              - nitric oxides concentration (parts per 10 million)
6. RM               - average number of rooms per dwelling
7. AGE              - proportion of owner-occupied units built prior to 1940
8. DIS              - weighted distances to five Boston employment centres
9. RAD              - index of accessibility to radial highways
10. TAX             - full-value property-tax rate per 10,000 dollars.
11. PTRATIO         - pupil-teacher ratio by town
12. B               - 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
13. LSTAT           - % lower status of the population
14. MEDV            - Median value of owner-occupied homes in 1000's dollars


# Step involved:
# 1.Exploratory Data Analysis: 
Here I wanted to gain important statistical insights from the data and the things that I checked for were the distributions of the different attributes, correlations of the attributes with each other and the target variable and I calculated important odds and proportions for the categorical attributes.
include the steps of: Missing value detection, outlier detection, data analysis with info() and describe() pandas function
# 2.Feature Engineering: 
Here we basically handles the missing value,outliers, do encoding, check data balancing,feature scalling etc.
in above case zero missing values are present, all features are in neumerical form hence no encoding required. Here we handled outliers with imputation techniques.Also perform feature scalling.
# 3. Model Building:
It's a regression problem hence we tried linear, DT, KNN, RF regression with hyperparameter tunning.
# 4. Model Evaluation:
As it's a regression problem so performance matrice will be score, MSE, RMSE,R2_score.
# Finally we finishes the project. with Random Forest Regressor Model and having the Training accuracy of 89% and Testing accuracy of 84%

