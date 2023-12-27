## Housing Price Prediction Model
### Overview
This repository contains Python code for a machine learning model designed to predict housing prices. The dataset used for this task includes various features related to housing characteristics. The model is built using multiple regression techniques, including Linear Regression, Ridge Regression, Lasso Regression, and Support Vector Regression (SVR). The performance of these models is evaluated, and the best-performing model is identified.

### Contents
1 - Data Loading and Inspection:

- The housing dataset is loaded using Pandas from a CSV file.
- Data is inspected to understand its structure and features.
- Delimiter issues are addressed, and column names are specified.

2 - Data Exploration:

- Missing values and duplicates are checked and handled appropriately.
- Descriptive statistics and visualizations, such as histograms and boxplots, are used to understand the distribution of features and identify potential outliers.

3 - Data Visualization:

- Histograms and correlation heatmaps are generated to visualize the distribution of features and explore relationships between variables.
- Scatterplots illustrate the relationship between each feature and the target variable (MEDV).

4 - Feature Selection:

- Features are separated into input features (X) and the target variable (y).

5 - Data Preprocessing:

- The dataset is split into training and testing sets using the train_test_split function from scikit-learn.

6 - Model Training/Model Pipeline:

- Multiple regression models (Linear Regression, Ridge Regression, Lasso Regression, and SVR) are trained using scikit-learn pipelines.
- Each pipeline includes feature scaling and the respective regression model.

7 - Model Evaluation:

- Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Percentage Error (MAPE), and R-squared (R2) scores are calculated for each model.
- Model performances are compared, and the best-performing model is identified.
