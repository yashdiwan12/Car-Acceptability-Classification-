# Car-Acceptability-Classification-
Car Acceptability Classification with Machine Learning
Project Overview
This project aims to predict how acceptable a car is for consumers by using machine learning methods. The main objective is to classify cars into categories such as "unacceptable," "acceptable," "good," or "very good" based on features that describe their price, maintenance costs, size, passenger capacity, luggage space, and safety. The project uses the Car Evaluation dataset from the UCI Machine Learning Repository, which is a standard benchmark for this kind of classification task.

How the Project Works
The workflow begins by gathering the dataset, which includes several key features for each car. These features are the buying price, maintenance cost, number of doors, number of persons the car can carry, size of the luggage boot, and safety rating. The final label for each car is its acceptability class, which the model tries to predict.

To process the data, all the features, which are originally in text form, are converted into numerical values. This is necessary because machine learning algorithms work with numbers rather than text. The conversion is done using a method called label encoding.

Once the data is ready, it is divided into two groups: one for training the model and one for testing it. The training group is used to teach the machine learning model how to recognize patterns in the data and associate them with the correct acceptability class. The testing group is used to check how well the model has learned and how accurately it can predict the acceptability of new, unseen cars.

A decision tree classifier is used as the machine learning model. This type of model works by asking a series of questions about the features of a car and following a path based on the answers, eventually leading to a prediction about the car's acceptability.

How Results Are Obtained
After the model is trained, it is evaluated using the test data. The model predicts the acceptability class for each car in the test group. The accuracy of these predictions is measured to see how often the model is correct. In addition to overall accuracy, a detailed report is generated that shows how well the model performs for each class, including measures of precision, recall, and how well it balances false positives and false negatives.

Summary
This project demonstrates the process of building a machine learning solution for a real-world classification problem. It covers data loading, preprocessing, model training, and evaluation. By following these steps, the project shows how to use open data and standard machine learning tools to solve practical problems in the automotive domain. The approach can be adapted to similar tasks in other fields where categorical data needs to be classified based on multiple features
