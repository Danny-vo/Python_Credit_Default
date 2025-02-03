# Machine_Learning_in_Python
Using pandas, numpy and sci-kit learn package to predict Credit Default Risk

Individual assignment for BUSA8001-Applied Predictive Analytics.

Objective: Predict the proabability of a customer default their credit based on 18 features (Annual Income, Level of Education, Number of Children, Occupation type, ...)

Method: Using numpy, pandas to clean up the data and impute missing values. Add dummy variables for nominal features using One Hot encoder. Data was standardized before being trained using Logistic Regression and Random Forest Classifier and Accuracy score was the criteria to assess the 2 models. 

Result:  Random Forest Classifier outperformed Logistic Regression Classifer both on Training and Test dataset.
