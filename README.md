# Loan-Repayment-Prediction
# Project Structure
Data Loading and Preprocessing: Load the dataset, handle missing values, encode categorical features, and scale numerical features.

Exploratory Data Analysis (EDA): Analyze key trends, detect outliers, and understand feature relationships.

# Model Development:

Train 45 different machine learning models.

Perform hyperparameter tuning to optimize performance.

# Evaluation:

Use multiple metrics: Log Loss, Recall, and Precision.

Select the best-performing model based on evaluation results.

Final Model: Save the best model for future inference.

# Dataset
Entries: 209,593

Features: 37

Target variable: label (binary — default or non-default)

# Key feature groups include:

Financial transaction history

Recharge behavior

Loan amount and repayment history

# Requirements
Python 3.8+

Libraries:

pandas

numpy

scikit-learn

matplotlib

seaborn

xgboost

lightgbm

catboost

(optional) optuna for hyperparameter tuning

# Install requirements:

bash
Copy
Edit
pip install pandas numpy scikit-learn matplotlib seaborn xgboost lightgbm catboost optuna
Usage
Clone the repository or download the notebook.

# Install the required libraries.

Open Project2.ipynb and run all the cells.

Review the evaluation metrics to analyze model performance.

# Results
The project compares a wide range of models and identifies the best one based on:

Lowest Log Loss

Highest Recall

Highest Precision

# Future Work
Implement advanced feature engineering

Test deep learning models (e.g., using TensorFlow or PyTorch)

Deploy the model as an API or integrate it into a loan management system
