Loan Approval Classification

Overview

This project predicts whether a loan application will be approved or
rejected using machine learning.

The notebook uses a loan dataset with 45,000 records and compares
several classification models, both with and without PCA.

Dataset Features

The dataset includes information such as: - Age - Gender - Education -
Income - Employment experience - Home ownership - Loan amount - Loan
intent - Interest rate - Loan-to-income percentage - Credit history
length - Credit score - Previous loan defaults

Target: loan_status - 1 = Approved - 0 = Not Approved

Project Steps

Load the dataset.

Explore the data using visualizations.

Handle missing values.

Encode categorical features.

Split the data into training and testing sets.

Scale the features using StandardScaler.

Apply PCA while retaining 95% of the variance.

Train and compare multiple classification models.

Compare model performance with and without PCA.

Machine Learning Models

The project evaluates: - Logistic Regression - Random Forest - XGBoost -
Gradient Boosting - K-Nearest Neighbors (KNN) - Decision Tree - Support
Vector Machine (SVM)

Results

Without PCA, XGBoost achieved the highest accuracy at approximately
93.72%.

With PCA, Support Vector Machine achieved approximately 91.58%,
while Logistic Regression achieved approximately 90.03%.

Overall, PCA reduced the number of features from 22 to 17
components, but it did not improve the best model's accuracy in this
experiment.

Technologies

Python

Pandas

NumPy

Matplotlib

Seaborn

Plotly

Scikit-learn

XGBoost

How to Run

Open NTI_project.ipynb in Google Colab or Jupyter Notebook,
make sure the required dataset and libraries are available, and run the
cells in order.
