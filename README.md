# Customer_churn  

## Description  

A machine learning model to analyize the data and finding insights to stop telecom company's customers from churning out to other telecom companies.

## Lab Environment

Jupyter Notebook (Anaconda Navigator)  

## Domain 

Telecom

## Task Done  

### A)	Data Manipulation  

### B)	Data Visualization  
  a.	Built a bar-plot for the ’InternetService’ column  

  b.	Built a histogram for the ‘tenure’ column  
 
  c.	Built a scatter-plot between ‘MonthlyCharges’ & ‘tenure’     
  
  d.	Built a box-plot between ‘tenure’ & ‘Contract’      

### C)	Linear Regression:  
   a.	Built a simple linear model where dependent variable is ‘MonthlyCharges’ and independent variable is ‘tenure’  
   	Divided the dataset into train and test sets in 70:30 ratio. Built the model on train set and predict the values on test set. After predicting the values, calculated the root mean square error.   

### D)	Logistic Regression:  
   a.	Built a simple logistic regression model where dependent variable is ‘Churn’ & independent variable is ‘MonthlyCharges’  
   	Divided the dataset in 65:35 ratio. Built the model on train set and predict the values on test set. Built the confusion matrix and calculated the accuracy score  

  b.	Built a multiple logistic regression model where dependent variable is ‘Churn’ & independent variables are ‘tenure’ & ‘MonthlyCharges’  
      Divided the dataset in 80:20 ratio. Built the model on train set and predict the values on test set. Built the confusion matrix and calculated the accuracy score  

### E)	Decision Tree:  
   a.	Built a decision tree model where dependent variable is ‘Churn’ & independent variable is ‘tenure’  
      Divided the dataset in 80:20 ratio. Built the model on train set and predict the values on test set. Built the confusion matrix and calculate the accuracy  

### F)	Random Forest:  
   a.	Built a Random Forest model where dependent variable is ‘Churn’ & independent variables are ‘tenure’ and ‘MonthlyCharges’    
   	Divided the dataset in 70:30 ratio. Built the model on train set and predict the values on test set. Built the confusion matrix and calculate the accuracy  
      
## Selected the best model based on accuracy  

Linear Regression: 29.15 (RMSE)  
Simple Logistic Regression: 0.74 (Accuracy)  
Multiple Logistic Regression: 0.95 (Accuracy)  
Decision Tree: 0.76 (Accuracy)  
Random Forest: 0.75 (Accuracy)  
