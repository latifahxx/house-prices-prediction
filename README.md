House Prices Prediction
Overview

This project predicts the sale price (SalePrice) of houses using machine learning. The model estimates prices for houses in the test dataset based on features provided in the training data.

Why This Project is Useful

Accurate house price prediction helps:

Buyers and sellers estimate fair market value.

Real estate professionals make informed decisions.

Data science learners practice regression, feature engineering, and model evaluation.

Dataset

train.csv: Training data with house features and target variable (SalePrice).

test.csv: Test data with house features only.

sample_submission.csv: Template for submitting predictions.

Libraries & Tools

Python: numpy, pandas, math

Data visualization: matplotlib, seaborn

Machine learning: scikit-learn

Project Workflow

Data Import & Exploration
Load datasets, inspect shapes, and explore distributions.

Data Cleaning

Remove columns with high missing values.

Fill missing numerical values with mean.

Encode categorical features using one-hot encoding.

Feature Selection & Alignment
Separate features from target variable and align test set columns.

Train/Test Split
Split training data into training (80%) and validation (20%) sets.

Model Training
Train a Linear Regression model on training data.

Evaluation
Assess performance with MAE, MSE, RMSE, and R² score.
Visualize actual vs predicted values.

Prediction & Export
Generate predictions for the test set and export results to predictions.xlsx.

How to Get Started

Clone the repository:

git clone https://github.com/latifahxx/house-prices-prediction.git


Install required libraries:

pip install numpy pandas matplotlib seaborn scikit-learn openpyxl


Place the dataset files (train.csv, test.csv, sample_submission.csv) in the project folder.

Run the main notebook or script to train the model and generate predictions.

Contribution

Contributions are welcome! You can:

Suggest improvements to the model or preprocessing steps.

Report issues or bugs.

Add more visualization or feature engineering techniques.