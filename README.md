# Capstone Data Science Course Project - Healthcare - Diabetes Detection

### Note:_This is an academic project completed by me as part of my PG Data Science programme_

### Summary:
This was a comprehensive project completed as part of the Data Science PG Programme. This covers classification algorithms over a dataset collected on health/diagnostic variables to predict of a person has diabetes or not based on the data points. Apart from extensive EDA to understand the distribution and other aspects of the data. Pre-processing was done to identify data which was missing or did not make sense within certain columns and imputation techniques were deployed to treat missing values. For classification the balance of classes was also reviewed and treated using SMOTE. Finally models were built and compared for accuracy on various metrics.Lastly the project contains a dashboard on the original data using Tableau

### Context:
This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.

### Problem Statement:
Build a model to accurately predict whether the patients in the dataset have diabetes or not?

### Dataset Description:
The datasets consists of several medical predictor variables and one target variable, Outcome. Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and so on.

|Variable | Description |
|-----|-----|
|Pregnancies | Number of times pregnant|
|Glucose | Plasma glucose concentration a 2 hours in an oral glucose tolerance test|
|BloodPressure | Diastolic blood pressure (mm Hg)|
|SkinThickness | Triceps skin fold thickness (mm)|
|Insulin | 2-Hour serum insulin (mu U/ml)|
|BMI | Body mass index (weight in kg/(height in m)^2)|
|DiabetesPedigreeFunction | Diabetes pedigree function|
|Age | Age (years)|
|Outcome | Class variable (0 or 1) 268 of 768 are 1, the others are 0|

### Approach:  

1.	Perform descriptive analysis. It is very important to understand the variables and corresponding values. We need to think through - Can minimum value of below listed columns be zero (0)? On these columns, a value of zero does not make sense and thus indicates missing value.
* Glucose
* BloodPressure
* SkinThickness
* Insulin
* BMI 
</br>Decide how to treat the zero values in these columns

2.	Visually explore these variable and look for the distribution of these variables using histograms. Treat the missing values accordingly.

3.	There are integer as well as float data-type of variables in this dataset. Create a count (frequency) plot describing the data types and the count of variables. 

4. Check the balance of the data (to review imbalanced classes for the classification problem) by plotting the count of outcomes by their value. Review findings and plan future course of actions.

5.	Create scatter charts between the pair of variables to understand the relationships. Describe findings.

6.	Perform correlation analysis. Visually explore it using a heat map.

7.	Devise strategies for model building. It is important to decide the right validation framework. Would Cross validation be useful in this scenario?

8.	Apply an appropriate classification algorithm to build a model. Compare various models with the results from KNN.

9.	Create a classification report by analysing sensitivity, specificity, AUC(ROC curve) etc. Decide what values of these parameter to settle for? any why?

10. Dashboard in tableau by choosing appropriate chart types and metrics useful for the business. The dashboard must entail the following:    
  * Pie chart to describe the diabetic/non-diabetic population
  * Scatter charts between relevant variables to analyse the relationships
  * Histogram/frequency charts to analyse the distribution of the data
  * Heatmap of correlation analysis among the relevant variables
  * Create bins of Age values – 20-25, 25-30, 30-35 etc. and analyse different variables for these age brackets using a bubble chart. 









