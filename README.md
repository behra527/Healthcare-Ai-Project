# Healthcare AI Project

A machine learning project based on healthcare data. The project covers data exploration preprocessing visualization model training evaluation and model saving using Joblib.

## Project Overview

The main goal of this project is to build a small healthcare classification system using Scikit-learn. The dataset was explored and prepared before training multiple machine learning models to predict test results.

## Project Workflow

1. Load the healthcare dataset
2. Explore the dataset and check its structure
3. Check missing values and duplicate records
4. Analyze numerical and categorical features
5. Perform exploratory data analysis and visualization
6. Create useful features such as Age Group and Stay Duration
7. Encode categorical features
8. Separate features and target variable
9. Split the data into training and testing sets
10. Scale the features
11. Train machine learning models
12. Evaluate model performance
13. Save the trained models using Joblib

## Models Used

- Logistic Regression
- Random Forest Classifier
- Support Vector Machine

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

## Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Classification Report

## Saved Models

Project Structure
Healthcare_AI_Project/
│
├── data/
│   └── healthcare_dataset.csv
│
├── healthcare_ai_project.ipynb
│
├── logistic_regression_model.pkl
├── random_forest_model.pkl
├── svm_model.pkl
├── scaler.pkl
│
├── README.md
└── requirements.txt
Installation

Clone the repository and install the required dependencies:

pip install -r requirements.txt
Running the Project

Open the Jupyter Notebook:

jupyter notebook

Then open:

healthcare_ai_project.ipynb

Run the notebook cells in order to reproduce the analysis and model training process.

Conclusion

This project demonstrates a complete machine learning workflow using healthcare data. It covers data analysis preprocessing feature engineering visualization model training evaluation and model saving.

The project was developed as a practical implementation of the machine learning concepts learned during the week and is organized for further development and deployment.
The trained models are saved using Joblib:

```text
logistic_regression_model.pkl
random_forest_model.pkl
svm_model.pkl
scaler.pkl
