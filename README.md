# House Pricing Prediction

## Description
This is a Kaggle House Price Prediction Competition - House Prices: Advanced Regression Techniques. 
The objective of the project is to perform data visulalization techniques to understand the insight of the given data using python.  
After performing the data analysis and data engineering, we use advanced regression techniques to make predictions.


## Software and Libraries
* python
* NumPy
* pandas
* seaborn
* matplotlib
* scikit-learn

## Datasets Used
The data is split equally into a training set, which will be used to create the model and a test set, which will be used to test model performance.
* test.csv - test dataset
* train.csv - train dataset

The dataset has 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa. 

## General Workflow
The general workflow used to create the model is:
### Data Preprocessing:
These preprocessing steps are integral to model performance later on as they improve the quality and interpretability of the dataset.
    * Step 01: Import the libraries
    * Step 02: Import the datasets
    * Step 03: Look at the data head/tail
    * Step 04: Check out the missing values in every feature.

### Data Analysis:
* Look out for Potential outliers in each variable
* Check for variables with higher correlation to SalePrice
* Plotting scatterplots of all features that have higher correlations(>0.5) with SalePrice
* Correlation Matrix

### Data Cleaning
* Input missing values in the dataset

### Data engineering
* Create new variables
* Variable transformation using label encoding
* Train and Test split

### Model Design 
* Explore different models and choosing whcih model has the best performance for the project. 

## License
MIT