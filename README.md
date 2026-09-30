# SALARY PREDICTION

This project is made to predict an employee's salary using Machine Learning. The system uses information such as age, work experience, and education to predict salary.

Dataset

The dataset contains 20 employee records and includes:

* Age
* Experience
* Education
* Salary

Salaryis the value that the Machine Learning model predicts.

Data Cleaning and Analysis

The data was checked for missing values, duplicate values, and invalid values. The dataset was then cleaned before training the models.

Graphs were also created to understand the data. The analysis showed that salary generally increases with experience and education level.

Feature Engineering

A new feature called Experience Group was created.

* 0–2 years → Beginner
* 3–5 years → Junior
* 6–10 years → Mid-Level
* 11+ years → Senior

Data Preparation

The data was divided into:

* 80% training data
* 20% testing data

Categorical data such as Education and Experience Group was converted into numbers using One-Hot Encoding.

Age and Experience were scaled using StandardScaler.

Machine Learning Models

Two Machine Learning models were trained:

1. Linear Regression
2. Random Forest Regressor

The models were compared using MAE, RMSE, and R² Score.

The Random Forest model achieved about 0.96 R² on the test data.

Validation

The Random Forest model was also tested using 5-fold cross-validation to check how well it performs on different parts of the dataset.

Model Saving

The trained Random Forest model was saved as:

salary_prediction_model.pkl

This saved model can be loaded later and used to predict the salary of a new employee.

 GUI Prototype

A simple Python GUI was created using Tkinter.

The user enters:

* Age
* Experience
* Education

The system then predicts the salary and displays the Experience Group.

Conclusion

This project demonstrates how Machine Learning can be used to predict salary. It includes data cleaning, data analysis, feature engineering, data preprocessing, model training, model testing, validation, model saving, and a GUI prototype.


