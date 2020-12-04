# Estimation with Multiple Linear Regression

This repository includes a simple implementation of the multiple linear regression model. I've made this implementation in 4 steps:  

**1- EDA (exploratory_data_analysis.ipynb) :** Understanding the data set by analyzing and visualizing.  

**2- Handling Missing Data & Outliers (handling_outliers.ipynb) :** 
There were no missing observations in the data set we used :innocent: but we have outliers : Solving the outlier problem by trying 3 different methods.  

**3- Data Transformation (data_transformation.ipynb) :** Converting categorical data into numerical before using them in learning model.  

**4 - Building a Model (multiple_linear_regression.ipynb) :** Building a regression model after making the final adjustments. Evaluating model performance.  
  
  # Dataset  
  * **Data :** Personal Medical Cost Dataset  
  * **Columns :**  
    * age: Age of primary beneficiary.  
    * sex: Insurance contractor gender: female, male.  
    * bmi: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height. Objective index of body weight (kg / m ^ 2) using the ratio of height to weight. Ideally 18.5 to 24.9.  
    * children: Number of children covered by health insurance. 
    * smoker: Smoking status 
    * region: the beneficiary's residential area in the US: northeast, southeast, southwest, northwest.  
    * charges: Individual medical costs billed by health insurance.  
 * [Download Dataset](https://www.kaggle.com/mirichoi0218/insurance)  
   
# Files  
* **insurance.csv :** original data set  
* **cleaned_data.csv :** dataset without outliers
* **final_data.csv :** dataset used in model  
* **exploratory_data_analysis.ipynb :** First notebook  
* **handling_outliers.ipynb :** Second notebook  
* **data_transformation.ipynb :** Third notebook  
* **multiple_linear_regression.ipynb :** Last notebook  
# Libraries  
* numpy
* pandas
* matplotlib
* seaborn
* sklearn
