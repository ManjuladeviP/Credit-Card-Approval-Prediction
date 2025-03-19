# Machine Learning Model Training and Evaluation

## Description
This project trains and evaluates multiple machine learning models for binary classification tasks, particularly in credit approval prediction. It uses various classification algorithms and techniques such as data preprocessing, feature scaling, handling class imbalance with SMOTE, and feature importance analysis.

## Features
- Generates a synthetic dataset if none exists.
- Handles missing values and encodes categorical data.
- Scales numerical features using StandardScaler.
- Handles class imbalance using SMOTE.
- Trains multiple models: Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, and XGBoost.
- Evaluates models using accuracy, confusion matrix, and classification reports.
- Analyzes feature importance for tree-based models.

## Requirements
Make sure you have the following dependencies installed:
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Imbalanced-learn

## Installation
1. Clone or download this repository.
2. Install the required dependencies using pip:
   ```sh
   pip install pandas numpy matplotlib seaborn scikit-learn xgboost imbalanced-learn
   ```

## Usage
1. Run the script:
   ```sh
   python model_training.py
   ```
2. The script will:
   - Check if a dataset exists, otherwise create a synthetic dataset.
   - Load and preprocess the dataset.
   - Handle class imbalance using SMOTE.
   - Split data into training and testing sets.
   - Train multiple classification models.
   - Evaluate the models and display results.
   - Analyze feature importance.

## File Structure
```
project-folder/
│-- model_training.py    # Main script for model training
│-- credit_card_data.csv # Dataset file (generated if not present)
│-- README.md            # Documentation


