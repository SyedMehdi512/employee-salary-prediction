# Employee Data Preprocessing and Salary Prediction

## Project Overview
This project focuses on preprocessing an employee dataset and preparing it for machine learning. Using Python and popular data science libraries, the notebook demonstrates data cleaning, feature engineering, data transformation, and salary prediction using Linear Regression.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

## Data Preprocessing Steps
- **Data Exploration:** Examining dataset information, statistical summaries, columns, and unique values.
- **Feature Removal:** Removing the irrelevant `id` column.
- **Date Processing:** Converting birth dates into age features.
- **Missing Value Handling:** Using median imputation for numerical columns and most-frequent imputation for categorical columns.
- **Outlier Handling:** Applying IQR-based capping to selected numerical features.
- **Feature Engineering:** Creating `salary_growth`, `experience_ratio`, `educ_level`, and `age_group` features.
- **Feature Scaling:** Applying StandardScaler to numerical columns.
- **Categorical Encoding:** Demonstrating binary, label, and ordinal encoding techniques.

## Machine Learning
The notebook uses Linear Regression to predict employee salary. The dataset is divided into training and testing sets using an 80/20 split.

## Model Evaluation
The model's performance is evaluated using:
- Mean Squared Error (MSE)
- R² Score

## Objective
To gain practical experience in data preprocessing, feature engineering, and preparing employee data for machine learning-based salary prediction.
