
CUNEF - Máster en ciencia de datos

Alba Rodríguez Berenguel
#

# CARD FRAUD CLASSIFICATION

This repository contains the final work of the master's degree in data science. The title of the project is **'Detection of fraudulent transactions with bank cards using classification techniques'**.

![Logo](https://blog.saginfotech.com/wp-content/uploads/2019/04/credit-card-frauds.jpg)

## DESCRIPTION

The objective is to obtain a model that is capable of classifying bank transactions as fraudulent or non-fraudulent, as well as being able to know which are the variables that most help the classification.

The data has been obtained from the Kaggle platform (https://www.kaggle.com/competitions/ieee-fraud-detection/). These were published for a contest organized by the IEEE in collaboration with Vesta, one of the pioneering companies in providing fraud prevention solutions.

There are two data sets: Transaction and Identity. The first one contains information about the transactions and the second one about the users. They have a common column with which they can be related. Many of the variables do not have a specific explanation, since many of them are anonymized to preserve the privacy of the users, so it is not possible to know what information they provide exactly. In the data dictionary (data_dictionary file) everything that is known about the various variables is expanded.

The target variable is isfraud and it refers to whether a transaction is fraudulent or not. It is coded with 1 if it is fraud and 0 if it is not.

All the phases of a Machine Learning project have been carried out: data analysis and cleaning, transformations, variable selection and modeling.

## CONTENT

The folders found in the project are the following:

- Data: In the raw folder are the unmodified raw data and in the processed folder are the already transformed data.
- Env: requirements.txt file.
- Html: Notebooks saved in html format.
- Models: Models saved in pickle format.
- Notebooks: Notebooks with which we have worked, listed according to the order we have followed in the project.
	- 01_EDA: Exploratory analysis (nulls, outliers, correlations, visualizations)
	- 02_Feature_Engineering: transformation of values, creation of new variables, construction of a preprocessor, selection of variables.
	- 03_Random_forest
	- 04_LogisticRegression
	- 05_XGBoost
	- 06_LightGBM
	- 07_Parameters_Optimization: Cross validation to find the best hyperparameters.
	- 08_Explainability: Explainability of the model.
	- 09_Dash: Dashboard.
