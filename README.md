# GrowthLink Data Science Task: Car Sales Prediction

## Project Overview
This project predicts the **car purchase amount** a customer is likely to spend based on their demographic and financial features.  
It helps businesses optimize marketing strategies and boost sales growth using machine learning techniques.

## Technologies Used
- Python
- Pandas
- Matplotlib and Seaborn
- Scikit-learn
- Joblib

## Dataset Features
- `customer name`
- `customer e-mail`
- `country`
- `gender`
- `age`
- `annual Salary`
- `credit card debt`
- `net worth`
- `car purchase amount` (Target Variable)

## Key Steps in the Project
1. **Data Loading**
2. **Exploratory Data Analysis (EDA)**
3. **Feature vs Target Relationship Visualization**
4. **Data Preprocessing**:
   - Removing unnecessary columns
   - Handling missing values
   - Detecting and removing outliers (using IQR method)
   - Feature scaling (Standardization)
5. **Train-Test Split**
6. **Model Building**:
   - Linear Regression
   - Decision Tree Regressor
   - Random Forest Regressor
7. **Model Evaluation and Comparison**
8. **Saving the Final Model** using Joblib

## Final Model Selected
- **Model**: Linear Regression
- **R² Score**: 1.00
- **Mean Squared Error (MSE)**: Near Zero

## Saved Model File
- **File Name**: `car_sales_model.pkl`
- **Saved Using**: Joblib for easy loading and deployment.

## How to Use This Project
1. Clone or download the repository.
2. Install the required dependencies (if needed).
3. Run the provided Jupyter Notebook or Python scripts.
4. Load the saved model and predict car purchase amounts for new customer data.
