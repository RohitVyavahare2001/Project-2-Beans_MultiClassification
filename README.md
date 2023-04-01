Bean Classification using Machine Learning
This project aims to classify seven different types of dry beans using machine learning algorithms. The dataset used in this project includes features such as form, shape, type, and structure of the beans. The target variable is the type of bean, and the task is to classify the beans based on their dimension and shape features only, with no external discriminatory features.

Dataset
The dataset used in this project contains information on seven types of dry beans - Barbunya, Bombay, Cali, Dermason, Horoz, Seker, and Sira. The dataset includes 13 features, including the target variable. The dataset has been pre-processed using the following steps:

Basic EDA was performed to find patterns, but no straight patterns were observed between features and target.
The target column was converted from categorical to numeric using dictionary encoding.
The data was scaled using Standard Scaler.
Feature selection was performed using Extra-Trees Classifier.
The target column was over-sampled using SMOTE to balance it.
Machine Learning Models
Five different machine learning algorithms were used to classify the beans:

Logistic Regression
Support Vector Machines (SVM)
Decision Tree
Random Forest
Naive-Bayes
Out of all these models, the Support Vector Machine (SVM) performed the best in terms of accuracy and precision, and hence was chosen as the final model for classification.

Conclusion
The project shows that machine learning algorithms can be effectively used to classify different types of dry beans. The Support Vector Machine (SVM) algorithm performed the best in this case. 
