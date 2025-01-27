# Titanic-Survival-Prediction-Using-Machine-Learning
# Project Overview
The goal of this project is to predict the survival of passengers aboard the Titanic using Logistic Regression, a binary classification algorithm. The project includes:

• Data preprocessing and cleaning
• Exploratory Data Analysis (EDA)
• Feature engineering
• Model training and evaluation
• Prediction on test data

# Dataset
The dataset used in this project is the Titanic dataset, which contains information about passengers, such as:
PassengerId: Unique ID for each passenger
Survived: Survival status (0 = No, 1 = Yes)
Pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
Name: Passenger name
Sex: Gender of the passenger
Age: Age in years
SibSp: Number of siblings/spouses aboard
Parch: Number of parents/children aboard
Ticket: Ticket number
Fare: Passenger fare
Cabin: Cabin number
Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

The dataset is split into:

train.csv: Training data with survival labels
test.csv: Test data without survival labels

# Methodology
1. Data Preprocessing:
• Handle missing values (e.g., impute Age and Embarked).
• Convert categorical variables (Sex, Embarked) into numerical format using one-hot encoding.
• Drop irrelevant columns (PassengerId, Name, Ticket, Cabin).

2. Exploratory Data Analysis (EDA):
• Visualize the distribution of features and their relationship with survival.
• Analyze correlations between features.

3.Feature Engineering:
• Create new features (e.g., family size from SibSp and Parch).
• Scale numerical features (e.g., Age, Fare).

4. Model Training:
• Split the data into training and validation sets.
• Train a Logistic Regression model using scikit-learn.

5. Model Evaluation:
• Evaluate the model using accuracy, precision, recall, and F1-score.
• Generate a confusion matrix.

6. Prediction:
• Predict survival for the test dataset and save the results.
Results
The Logistic Regression model achieved the following performance metrics:

Accuracy: 80%

Precision:81%

Recall: 80%

F1-Score: 80%

The confusion matrix is included in the notebook.
