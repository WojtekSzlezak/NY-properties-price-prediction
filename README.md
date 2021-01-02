# NY-properties-price-prediction

Data science project containing data cleaning, exploratory data analysis and machine learning - predicting NY properties prices - regression problem

# Requirements

The project was developed using python 3.6.9

### Packages

Following packages were used:

- Pandas 1.0.5
- Numpy 1.18.5
- Sklearn 0.22.2.post1
- Plotly 4.4.1
- Matplotlib 3.2.2
- Seaborn 0.10.1
- Joblib 0.16.0
- Xgboost 0.90

### Software

Project was created using Google Colaboratory and this is recommended environment for reviewing and executing the code. Google Colaboratory already have all required packages installed. Google Colab is accessible via google drive, so there is no need to install any software. Otherwise you can use Jupyter Notebook. This option may require to adjust display options for plotly graphics and to install missing libraries with pip install command.

### Data

Dataset used in the project is attached to the repository files. Please download 'nyc-rolling-sales.csv' directly from repository and upload it to your Google Colaboratory notebook working files using 'Upload to session storage' button in 'Files' section.

### Code

Project code is avalaible in 'NY_properties_price_prediction.ipynb' file. To execute the code please add file to the google drive and open it in Google Colaboratory or open the file directly from github using 'Open in colab' button. Then please upload the dataset (please see above) and use 'Run all' option in 'Runtime' menu.

# Project description

The goal of the project was to create an effective model being able to predict New York properties market prices. Dataset used in the project is a record of every building or building unit (apartment, etc.) sold in the New York City property market over a 12-months period (2016-09-01 till 2017-08-31). Dataset consists of 22 self-described columns.

The project consists of three parts: data cleaning, exploratory data analysis and machine learning.

# Summary

Best results from all of the models used in the project (linear regression, decision tree regressor random forest regressor, XGBoost regressor) were achieved by XGBoost regressor. The r2 score and mean absolute error metrics were used to evaluate models.

The best model obtained about 70-71% in the R2 score metric.
