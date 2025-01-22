# Titanic-dataset-using-ML
Project Description:
This project analyzes the Titanic dataset to predict passenger survival using machine learning techniques. It involves preprocessing the data, handling missing values, exploring relationships through visualizations, and building a classification model to estimate survival likelihood. The Random Forest algorithm is employed for prediction, and its performance is evaluated using accuracy metrics, classification reports, and confusion matrices.

Table of Contents
. Introduction
. Dataset
. Technologies Used
. Project Workflow
. Model Evaluation
. Results
. How to Use
. Contributions

Introduction
The sinking of the Titanic is one of the most infamous maritime disasters in history. This project aims to leverage machine learning to predict whether a passenger survived or not, based on features such as:

. Passenger class (Pclass)
. Gender (Sex)
. Age
. Number of siblings/spouses aboard (SibSp)
. Number of parents/children aboard (Parch)
. Ticket fare (Fare)
. Embarkation point (Embarked)

Dataset
The dataset used in this project is the publicly available Titanic dataset. It includes the following key fields:

. Survived: Survival (0 = No, 1 = Yes)
. Pclass: Ticket class (1 = First, 2 = Second, 3 = Third)
. Sex: Gender
. Age: Age in years
. SibSp: Number of siblings/spouses aboard
. Parch: Number of parents/children aboard
. Fare: Passenger fare
. Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

Technologies Used
. Programming Language: Python
Libraries:
. Data Manipulation: pandas, numpy
. Visualization: matplotlib, seaborn
. Machine Learning: scikit-learn

Project Workflow
1. Data Loading and Exploration
 . Load the Titanic dataset using pandas.
.  Perform initial exploration with .info(), .describe(), and .head() to understand the dataset's structure.
2. Data Preprocessing
. Handle missing values (e.g., impute missing Age values with the mean).
. Encode categorical variables (Sex and Embarked) using LabelEncoder.
. Select features for the model: Pclass, Sex, Age, SibSp, Parch, Fare.

3. Exploratory Data Analysis (EDA)
. Visualize key features and their relationship with survival using seaborn and matplotlib:
. Age and Fare distributions.
. Survival counts.
. Passenger class distribution.
4. Model Building
. Split the dataset into training and testing sets using train_test_split.
. Train a Random Forest Classifier with 100 trees.
5. Model Evaluation
. Evaluate predictions using:
. Accuracy score.
. Classification report.
. Confusion matrix.

Model Evaluation
. Accuracy: The model achieved an accuracy score of approximately 82% (replace with actual value from your output).
Key Insights:
. Certain features (e.g., gender and class) significantly impact survival rates.
. Visualizations confirmed expected trends, such as higher survival rates among women and first-class passengers.

Results
The model provides a robust approach to predicting passenger survival based on available features. It demonstrates the potential of machine learning in addressing classification problems.




