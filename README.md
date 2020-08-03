# Customer_churn  

## Description  

A machine learning model to analyize the data and finding insights to stop telecom company's customers from churning out to other telecom companies.

## Lab Environment

Jupyter Notebook (Anaconda Navigator)  

## Domain 

Telecom

## Task Done  

### A)	Data Manipulation:  
   a.	Extracted the 5th column & store it in ‘customer_5’  
   b.	Extracted the 15th column & store it in ‘customer_15’  
   c.	Extracted all the male senior citizens whose Payment Method is Electronic check & store the result in ‘senior_male_electronic’  
   d.	Extracted all those customers whose tenure is greater than 70 months or their Monthly charges is more than 100$ & store the result in ‘customer_total_tenure’  
   e.	Extracted all the customers whose Contract is of two years, payment method is Mailed check & the value of Churn is ‘Yes’ & store the result in ‘two_mail_yes’  
   f.	Extracted 333 random records from the customer_churn dataframe & store the result in ‘customer_333’  
   g.	Get the count of different levels from the ‘Churn’ column  

### B)	Data Visualization:  
   a.	Built a bar-plot for the ’InternetService’ column:  
   i.	Set x-axis label to ‘Categories of Internet Service’  
   ii.	Set y-axis label to ‘Count of Categories’  
   iii.	Set the title of plot to be ‘Distribution of Internet Service’  
   iv.	Set the color of the bars to be ‘orange’  

  b.	Built a histogram for the ‘tenure’ column:  
  i.	Set the number of bins to be 30  
  ii.	Set the color of the bins  to be ‘green’  
  iii.	Assigned the title ‘Distribution of tenure’  
  
  c.	Built a scatter-plot between ‘MonthlyCharges’ & ‘tenure’. Map ‘MonthlyCharges’ to the y-axis & ‘tenure’ to the ‘x-axis’:  
  i.	Assigned the points a color of ‘brown’  
  ii.	Set the x-axis label to ‘Tenure of customer’  
  iii.	Set the y-axis label to ‘Monthly Charges of customer’  
  iv.	Set the title to ‘Tenure vs Monthly Charges’  
  d.	Built a box-plot between ‘tenure’ & ‘Contract’. Map ‘tenure’ on the y-axis & ‘Contract’ on the x-axis.    

### C)	Linear Regression:  
   a.	Built a simple linear model where dependent variable is ‘MonthlyCharges’ and independent variable is ‘tenure’  
   i.	Divided the dataset into train and test sets in 70:30 ratio.   
   ii.	Built the model on train set and predict the values on test set  
   iii.	After predicting the values, finded the root mean square error  
   iv.	Finded the error in prediction & store the result in ‘error’  
   v.	Finded the root mean square error  

### D)	Logistic Regression:  
   a.	Built a simple logistic regression model where dependent variable is ‘Churn’ & independent variable is ‘MonthlyCharges’  
   i.	Divided the dataset in 65:35 ratio  
   ii.	Built the model on train set and predict the values on test set  
   iii. Built the confusion matrix and get the accuracy score  

  b.	Built a multiple logistic regression model where dependent variable is ‘Churn’ & independent variables are ‘tenure’ & ‘MonthlyCharges’  
  i.	Divided the dataset in 80:20 ratio  
  ii.	Built the model on train set and predict the values on test set  
  iii.	Built the confusion matrix and get the accuracy score  

### E)	Decision Tree:  
   a.	Built a decision tree model where dependent variable is ‘Churn’ & independent variable is ‘tenure’  
   i.	Divided the dataset in 80:20 ratio  
   ii.	Built the model on train set and predict the values on test set  
   iii.Built the confusion matrix and calculate the accuracy  

### F)	Random Forest:  
   a.	Built a Random Forest model where dependent variable is ‘Churn’ & independent variables are ‘tenure’ and ‘MonthlyCharges’  
   i.	Divided the dataset in 70:30 ratio  
   ii.	Built the model on train set and predict the values on test set  
   iii. Built the confusion matrix and calculate the accuracy  

