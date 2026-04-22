# Data Cleaning Practice - Titanic Dataset

This repository contains a data cleaning and preprocessing exercise using Kaggle's famous Titanic dataset. The goal is to prepare the data for further statistical analysis or modeling.

[Versión en Español aquí](README.md)

## Repository Content

- `Cleaning_TITANIC_2024.ipynb`: Jupyter Notebook containing the entire data cleaning process.
- `Titanic/`: Folder containing the original datasets (`train.csv`, `test.csv`, and `gender_submission.csv`).

## Process Description

The following tasks are performed in the notebook:
1. **Descriptive Statistics**: Initial data exploration.
2. **Column Removal**: Removal of variables that do not add value to the initial model (such as 'Name').
3. **Missing Value Imputation**: Using `SimpleImputer` for categorical variables.
4. **Numerical Variable Treatment**: Imputing the mean for the 'Age' column and converting it to an integer type.
5. **Categorical Variable Encoding**: Applying One-Hot Encoding to the 'Sex' and 'Embarked' variables.
6. **Data Export**: Generating CSV files with the cleaned data.

## Instructions for Use

To run the code locally:
1. Clone this repository.
2. Ensure you have the necessary libraries installed (`pandas`, `numpy`, `scikit-learn`).
3. **Important Note**: In the notebook, you will need to update the load and save paths for the CSV files to match your local environment or Google Colab.

## Technologies Used

- Python
- Pandas
- Numpy
- Scikit-learn (SimpleImputer, OneHotEncoder)
- Jupyter Notebook / Google Colab
