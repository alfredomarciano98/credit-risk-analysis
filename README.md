# Analyzing Risky Loan


Many people struggle to get loans due to insufficient or non-existent credit histories. And, unfortunately, this population is often taken advantage of by untrustworthy lenders. Home Credit strives to broaden financial inclusion for the unbanked population by providing a positive and safe borrowing experience. In order to make sure this underserved population has a positive loan experience, Home Credit makes use of a variety of alternative data to predict their clients' repayment abilities.

In this repository I tried to do some analysis including EDA, feature engineering, etc to build predictive model using simple classification model such as Logistic Regression so I could find the stastical inference between properties and the target class. I am using data provided by Home Credit from https://www.kaggle.com/c/home-credit-default-risk/

I divide it into 3 notebooks:
* Data Understanding: In this notebook I tried to explore about the dataset, checking the available data, the data types for every column, and Exploratory Data Analysis to draw some conclusions about the data.
* Data Preparation: This is where I prepare the dataset before modelling steps, such as encoding categorical data, remove anomaly data, and imputating data to create final dataset used for modelling
* Data Modelling and Evaluation: The final notebook will tell when I create model to predict which customer will defaulted the loan and evaluate it using ROC AUC

I believe all my works are not perfect yet, that's why I welcome any suggestion that could improve my works. Thank you!

Reference:
https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Lasso.html
https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html
https://towardsdatascience.com/feature-selection-using-regularisation-a3678b71e499
https://towardsdatascience.com/how-to-perform-lasso-and-ridge-regression-in-python-3b3b75541ad8
https://towardsdatascience.com/feature-engineering-for-machine-learning-3a5e293a5114
https://towardsdatascience.com/how-to-calibrate-undersampled-model-scores-8f3319c1ea5b
https://towardsdatascience.com/dealing-with-imbalanced-classes-in-machine-learning-d43d6fa19d2
Buuren, Oudshoorn.2011.mice: Multivariate Imputation by Chained Equations in R.Jurnal of Statistical Software.45(3)
