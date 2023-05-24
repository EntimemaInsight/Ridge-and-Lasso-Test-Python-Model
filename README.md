# Ridge and Lasso Test - Python Model

This repository contains a Python model that demonstrates the use of Ridge and Lasso regression techniques for predicting the fuel efficiency (mpg) of vehicles.
The model uses the scikit-learn library and performs data preprocessing, exploratory data analysis, feature scaling, and regression modeling.

## Description

The main goal of this project is to showcase the application of Ridge and Lasso regression techniques on a vehicle dataset. The dataset used is "vehicules_par.csv" and contains information about various vehicles, including features like cylinders, displacement, horsepower, weight, acceleration, and model year.

The Python model performs the following steps:

1. Data preprocessing:
   - The dataset is imported using pandas.
   - Missing values marked as "?" in the "horsepower" column are replaced with the most frequent value using SimpleImputer.
   - The data is checked for missing values.

2. Exploratory data analysis:
   - Distributions of predictors and the dependent variable (mpg) are visualized using seaborn.
   - Skewness in the predictors and the dependent variable is examined.

3. Predictors and response scaling:
   - The predictors (cylinders, displacement, horsepower, weight, acceleration, model year) are scaled using StandardScaler.
   - The response variable (mpg) is scaled using StandardScaler.

4. Model training and evaluation:
   - The data is split into training and testing sets using train_test_split.
   - Linear regression, Ridge regression, and Lasso regression models are created using scikit-learn.
   - The models are trained on the training data.
   - The models are evaluated using R-squared score on the testing data.

## Dependencies

The following dependencies are required to run the Python model:

- numpy
- pandas
- matplotlib
- statsmodels
- seaborn
- scikit-learn

## License

This project is licensed under the MIT License.

## Credits

This project was created by Aleksandar Dimitrov and is licensed under the MIT License. If you have any questions or comments, feel free to contact me at alexi.zein@gmail.com.

