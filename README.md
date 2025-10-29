# Expected-CTC-Calculator-
Machine learning Expected CTC Calculator 
This is a Machine learning project to calculate the Expected CTC based on the variables like total experience, work experience in fields, graduation year, Type : Pg/UG etc..... 

In this project First of all i do Data cleaning and then handling missing values and remove duplicates after that I just Encode them using One hot Encoder and after that split the Data in train and test after that Use 3 models to check which one is better (Linear Regression, XGboost, Random Forest Classifier). When I Use Linear Regression algorithm i do Feature Scaling after that i got an accuracy of 98% and after checking both random forest and XGboost 99.5% of accuracy therefore i check the correlation between the variables i found current CTC is 0.98% correlated so it may create an issue of Overfitting or only depend on one variable so I try without Current CTC when user enter 0 Current CTC the model which is select will be different as compare to when the user put any value.... 

This is my whole Idea of this project.
