# Healthcare AI Project

A practical machine learning project built using a healthcare dataset. The project covers the complete machine learning workflow from data exploration and preprocessing to model training evaluation and model saving with Joblib.

## Project Overview

The goal of this project is to build a healthcare classification system that predicts patient test results using different machine learning algorithms.

The project includes exploratory data analysis feature engineering categorical encoding feature scaling model training and performance evaluation.

## Dataset

The project uses a healthcare dataset containing patient information such as:

- Age
- Gender
- Blood Type
- Medical Condition
- Admission Type
- Insurance Provider
- Medication
- Test Results
- Billing Amount
- Hospital Stay Information

The dataset is used for educational and machine learning practice purposes.

## Project Workflow

The project follows these main steps:

1. Load the healthcare dataset
2. Explore the dataset structure
3. Check data types and dataset information
4. Check missing values
5. Check duplicate records
6. Analyze numerical features
7. Analyze categorical features
8. Perform exploratory data analysis
9. Visualize categorical and numerical distributions
10. Analyze relationships between healthcare features
11. Create Age Groups
12. Calculate hospital Stay Duration
13. Perform monthly stay duration analysis
14. Encode categorical features
15. Separate features and target variable
16. Split the dataset into training and testing sets
17. Scale the input features
18. Train multiple machine learning models
19. Evaluate model performance
20. Save trained models using Joblib

## Machine Learning Models

Three classification models were trained and evaluated:

- Logistic Regression
- Random Forest Classifier
- Support Vector Machine

## Model Evaluation

The models were evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- Classification Report

These metrics were used to compare the performance of the trained models.
## Models Wights link 
https://drive.google.com/drive/folders/1Orfk2hC_Bk71QqmmMlJClZYfgxP4SXyL?usp=sharing

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

## Project Structure

```text



- `notebooks/healthcare_ai_project.ipynb` - Main Jupyter Notebook containing data analysis and machine learning workflow
- `README.md` - Project documentation
- `requirements.txt` - Required Python libraries
- `.gitignore` - Files excluded from Git tracking

The healthcare dataset and trained model files are excluded from Git tracking because of file size and repository management considerations.

Installation

Clone the repository:

git clone https://github.com/behra527/Healthcare-Ai-Project.git

Move into the project directory:

cd Healthcare-Ai-Project

Install the required dependencies:

pip install -r requirements.txt
Running the Project

Start Jupyter Notebook:

jupyter notebook

Open the following notebook:

notebooks/healthcare_ai_project.ipynb

Run the notebook cells in order to reproduce the data analysis preprocessing model training and evaluation workflow.

Model Saving

The trained models were saved locally using Joblib:

logistic_regression_model.pkl
random_forest_model.pkl
svm_model.pkl
scaler.pkl

These files are excluded from the GitHub repository using .gitignore.

The scaler is saved separately because the trained models use standardized input features.

Key Learning Outcomes

Through this project I practiced:

Healthcare dataset exploration
Data preprocessing
Exploratory data analysis
Data visualization
Feature engineering
Categorical encoding
Feature scaling
Classification algorithms
Model evaluation
Model persistence using Joblib
Git and GitHub project management
Conclusion

This project demonstrates a complete machine learning workflow using healthcare data. It starts with data exploration and preprocessing and continues through feature engineering visualization model training evaluation and model saving.

The project provided practical experience in applying Scikit-learn classification algorithms and following a structured machine learning workflow from raw data to trained models.
