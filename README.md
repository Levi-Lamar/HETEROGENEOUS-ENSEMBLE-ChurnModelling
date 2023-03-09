# HETEROGENEOUS-ENSEMBLE-ChurnModelling
A PREDICTIVE ANALYSIS of a Churn_Modelling using HETEROGENEOUS ENSEMBLE
The goal is to predict the medical cost of a patient based on various features such as age, sex, BMI, etc. For this task, we will use three different models: a Random Forest, a Support Vector Machine (SVM), and a Gradient Boosting Regressor.

In this project, you first load the Churn_Modelling dataset and split it into features and target. We then split the data into train and test sets and scale the features using StandardScaler. We define three different base models: a Random Forest, an SVM, and a Gradient Boosting Regressor. We then train each model on a different subset of the data and make predictions using each model. Finally, we combine the predictions using simple averaging and evaluate the performance of the ensemble and each individual model using the mean squared error (MSE).

Dataset

The dataset used in this project is [Churn_Modelling.csv](https://github.com/Levi-Lamar/HETEROGENEOUS-ENSEMBLE-ChurnModelling/files/10929061/Churn_Modelling.csv)


Which contains information about the customer details. The dataset includes 10000 instances and 13 attributes including CreditScore of customers registered.

Evaluation Metrics

The performance of the linear regression model will be evaluated using the following metrics:

Random Forest MSE, SVM MSE, Gradient Boosting MSE, Ensemble MSE
