# Breast Cancer Classification with SVM

This project uses the breast cancer dataset included in `sklearn.datasets` to perform predictive analysis using Support Vector Machines (SVM). Different kernels (`linear`, `rbf`, `sigmoid`) and `gamma` values ​​are compared to evaluate the model's performance.

## Contents

- Loading and exploring the dataset
- Basic cleaning (null checking and summary statistics)
- Separating the training and test sets
- Training SVM models with different hyperparameters
- Evaluation with metrics such as precision, accuracy, and confusion matrix

## Technologies

- Python
- Scikit-learn
- Pandas

## Results

The script prints for each kernel and gamma combination:

- Accuracy
- Precision

It also displays a final classification report and a confusion matrix using a linear model as a final reference.
