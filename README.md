# Lab-exam-Binary-Classification-
In this dataset there are 2 independent variables and 1 dependent variable - Binary  classification
# Classification using Logistic Regression
# To build a classification model using Logistic Regression and evaluate its performance.
- Dataset used: (/content/Lab_Exam_binary_classification_dataset.csv)
- Features (X): Input variables
- Target (y): Output variable (Yes/No → converted to 0/1)
# Exploratory Data Analysis
Handled missing values
- Mapped target values (Yes → 1, No → 0)
- Removed NaN values in target column
Model used is Logistic Regression()
# Decision Boundary
Logistic Regression creates a linear decision boundary. Since the data was non-linear, the model could not separate classes properly. 
Polynomial features were used to create a non-linear decision boundary, improving the model performance.
# Classification report and confusion matrix
Accuracy - 0.79
Confusion Matrix - Confusion Matrix:
[[158  42]
 [  0   0]]
Precision, Recall, F1-score -
0.79, 1, 0.88 for 0
0.0, 0.0, 0.0 for 1


