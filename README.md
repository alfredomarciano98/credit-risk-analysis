# credit-risk-analysis-using-logistic-regression


Many people struggle to get loans due to insufficient or non-existent credit histories. And, unfortunately, this population is often taken advantage of by untrustworthy lenders. Home Credit strives to broaden financial inclusion for the unbanked population by providing a positive and safe borrowing experience. In order to make sure this underserved population has a positive loan experience, Home Credit makes use of a variety of alternative data to predict their clients' repayment abilities.

In this repository I tried to do some analysis including EDA, feature engineering, etc to build predictive model using simple classification model such as Logistic Regression so I could find the stastical inference between properties and the target class. I am using data provided by Home Credit from https://www.kaggle.com/c/home-credit-default-risk/

I divide it into 3 notebooks: Data Understanding and Exploratory Data Analysis, Data Preparation, and Data Modelling with Evaluation.
  Data Understanding and EDA          : The first notebook where I explore the data wholly, checking the basic statistics, data types, etc. Then I did EDA to find the anomaly                                            of the data, to find features which helps differs customers who repay or not, etc.
  Data Preparation                    : This notebook shows the step I done to prepare the dataset before trained using machine learning method such as the way I treat the                                                 anomaly, imputed the missing data, and using regularization for feature selection and prevent the model overfitting the train dataset.
  Data Modelling and Evaluation       : Steps where I trained the model using data after all preparation, use it to predict train dataset, checking whether the model overfit or                                           not and finally use it to predict the oot data.

I believe all my works are not perfect yet, that's why I welcome any suggestion that could improve my works. Thank you!
