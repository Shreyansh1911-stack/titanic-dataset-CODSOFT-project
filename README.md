Titanic Survival Prediction Project

A machine learning project to predict passenger survival on the Titanic. This was completed as part of the Codsoft internship.

 How to Run :

To run this project on your own machine, follow these steps.

Prerequisites

You will need Python and the following libraries installed. You can install them using pip:
pip install pandas numpy scikit-learn


>My Process:
Data Exploration and Cleaning: Loaded the dataset and handled missing values, particularly for the 'Age' column, by filling them with the median.

Feature Engineering: Converted categorical features like 'Sex' and 'Embarked' into a numerical format that the model can understand.

Model Training: Trained a Logistic Regression model because it is a simple yet effective algorithm for binary classification tasks.

Evaluation: The model was tested against an unseen portion of the dataset to evaluate its performance.
