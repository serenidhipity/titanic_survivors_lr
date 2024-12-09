# titanic_survivors_lr
This project is part of my university coursework, where I apply machine learning techniques to analyze real-world datasets. The goal is to predict passenger survival on the Titanic using **Logistic Regression**. The analysis is performed using Python and Jupyter Notebook, incorporating various data science libraries.


## Project Overview
This project uses data from the Titanic disaster, available from the Kaggle Titanic dataset, to predict whether a passenger survived based on features like age, sex, passenger class, and more. A Logistic Regression model is trained and evaluated to perform this binary classification task.

---

## Dataset

The dataset used is the **Titanic: Machine Learning from Disaster** dataset from Kaggle. It includes:
- **Train.csv**: Contains labeled data for training the model.
- **Test.csv**: Contains unlabeled data for testing predictions.

### Key Features:
- **Pclass**: Passenger class (1st, 2nd, 3rd)
- **Sex**: Gender
- **Age**: Age of the passenger
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Fare**: Ticket price
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

---

## Results
The Logistic Regression model achieved:

Accuracy: 0.782
Log loss: 0.504
ROC-AUC: 0.838
