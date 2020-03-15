# Machine-Learning-Project-Regression-to-Predict-onset-of-Diabetes
Predicting onset of Diabetes using Linear and Polynomial Regression
# Project
## Predicting the progression of diabetes based on different demographic determinants

The goal of this project is to use different machine learning models to predict the progression of diabetes one year after baseline. There are 10 independent variables that are used for the prediction of the disease progression namely- age, sex, body-mass index, average blood pressure, and six blood serum measurements: low density lipoproteins (LDL), high density lipoproteins (HDL), total cholesterol (TC), triglyceride (TG), serum concentration of lamotrigine (LTG), glucose (GLU). The data was originally used in Lars Paper and has been scraped off from the following website using beautiful soup library and then it is finally read in to a text file. The text file is then converted in to excel file and is then read in to a pandas dataframe.

The data set has been normalized to have zero mean and variance of 1 and split in to training set and test set. The model is evaluated on the test set. Different models are evaluated that reduces the error or cost in predicting the correct output response varible (progression in diabetes in 1 year) such as:

* Linear Regression with single Variable
* Linear Regression with Multiple Variables
* Polynomial Regression (Regularized and Unregularized)

The training set is used for training the model. After the model is fitted on the training set, it is evaluated on both the training set and the test set. The model with the lowest cost or error in the test data set is concluded as the final model to be used for prediction of response variable. 

# Data
Data has been obtained from:
https://web.stanford.edu/~hastie/Papers/LARS/diabetes.data

# Programming Language
Python 3.6 has been used for this project.

# Libraries
Following libraries have been used in this project:
* numpy
* pandas
* matplotlib
* seaborn
* BeautifulSoup
* sklearn

# Statistical Methodology
* Data Wrangling
* Data Visualization
* Exploratory Analysis
* Linear Regression with single Variable
* Linear Regression with Multiple Variables
* Polynomial Regression (Regularized and Unregularized)

**Notebook**:  
Python notebook file is available with this project and is named: 
Diabetes_ML.ipynb

**Powerpoint Summary**:
diabetes_regression.pptx
