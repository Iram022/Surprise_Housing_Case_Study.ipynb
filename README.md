# Housing Price Prediction of Austria

This project aims to predict housing prices using machine learning techniques—**Ridge** and **Lasso Regression**. The dataset includes various house-related features like square footage, garage area, basement condition, etc. The goal is to build a regression model that accurately predicts house prices and highlights the most influential features.

## Objective

- Predict house prices using regression techniques.
- Perform data cleaning, transformation, and feature engineering.
- Use Ridge and Lasso regression for feature selection and regularization.

## Features & Methodology

- **Data Cleaning**: Handled missing values and outliers.
- **Exploratory Data Analysis (EDA)**: Used heatmaps, boxplots, and pairplots to understand relationships.
- **Feature Engineering**: Created new features like `Age` and converted categorical variables using dummy encoding.
- **Modeling**:
  - Ridge and Lasso Regression
  - Hyperparameter tuning using `GridSearchCV`
  - Evaluation using R² and RMSE
- **Key Findings**:
  - `GrLivArea`, `GarageCars`, and `PoolArea` were among the most influential features.

## Tech Stack

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- Google Colab

## Results

- **Best Ridge α**: 100
- **Best Lasso α**: 0.001
- Achieved good performance on test data and identified key drivers of house prices.

## Future Scope

- Apply advanced models like XGBoost or Random Forest
- Use SHAP or LIME for explainability
- Deploy as a web app using Streamlit



### Files Included

- `Surprise_Housing_Case_Study.ipynb`: Main Colab notebook
- `DS_INT_IRAMFATIMA.pdf`: Detailed report

##  How to Run

1. Clone this repo
2. Open the `.ipynb` file in Google Colab or Jupyter Notebook
3. Run all cells
