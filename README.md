# Binary Classification

# Objective
To apply the models learnt from the Udemy course "Python for Machine Learning and Data Science Bootcamp".

# Dataset
The dataset is available on kaggle - "Default of Credit Card Clients Dataset".  
Link to the website - https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset
## Description of Dataset
This dataset contains information on default payments, demographic factors, credit data, history of payment, and bill statements of credit card clients in Taiwan from April 2005 to September 2005.

There are 25 variables which contain the following information:
* Limit Balance of the Customers
* Customers details like age, gender, education
* Payment details 
* Default details

# Solution
To develop a suitable model to predict if a new customer will default the payment next month, given the requisite information. Accuracy score from sklearn was used to compare the efficiency of the models. For KNN Classifier, SVM and Neural Networks, the data was scaled using Standard Scaler.

# Models
Given below are the models that were applied alongwith their accuracy scores:
* Logistic Regression : 0.78
* Decision Tree Classifier : 0.73
* Random Forest Classifier : 0.82
* K Nearest Neighbour Classifier : 0.81 (after doing parameter tuning)
* Support Vector Machines : 0.83
* Neural Networks : 0.82

# Conclusion
Support Vector Machines gave predictions with the highest accuracy among the applied models.  
Based on my learning, scaling the data with Standard Scaler and then applying Support Vector Machines model would be recommended to solve this problem.
