# Marketing Sales Prediction Using Machine Learning

## 📌 Project Overview

This project focuses on analyzing marketing campaign data and predicting sales using Machine Learning techniques.

The objective is to understand how different marketing activities, customer segments, website traffic, and conversion rates relate to sales performance.

The project includes data cleaning, Exploratory Data Analysis (EDA), feature engineering, statistical analysis, and regression modelling.

## 🎯 Project Objectives

- Analyze marketing campaign data.
- Identify relationships between marketing activities and sales.
- Handle missing values and outliers.
- Perform skewness analysis and data transformation.
- Analyze multicollinearity using VIF.
- Build and evaluate regression models.
- Predict sales using machine learning.

## 📂 Dataset Features

The dataset contains the following features:

- TV_Ad_Spend
- Social_Media_Spend
- Discount_Offers
- Search_Engine_Marketing_Spend
- Website_Traffic
- Conversion_Rate
- Product_Category
- Region
- Customer_Segment
- Sales (Target Variable)

## 🛠️ Technologies & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Statsmodels
- Scikit-learn
- Jupyter Notebook

## 🔍 Project Workflow

### 1. Data Cleaning
- Data inspection
- Missing value treatment
- Duplicate checking
- Data preprocessing

### 2. Exploratory Data Analysis (EDA)
- Univariate Analysis
- Bivariate Analysis
- Correlation Analysis
- Distribution Analysis
- Data Visualization

### 3. Outlier & Skewness Treatment
- IQR Method
- Outlier Detection
- Outlier Clipping
- Skewness Analysis
- Power Transformation

### 4. Feature Engineering
- Categorical Encoding
- One-Hot Encoding
- Feature Scaling using StandardScaler

### 5. Statistical Analysis
- Variance Inflation Factor (VIF)
- Shapiro-Wilk Test
- Breusch-Pagan Test
- White Test
- Durbin-Watson Test
- Residual Analysis

### 6. Machine Learning Models
- Linear Regression
- Ridge Regression
- Lasso Regression

### 7. Model Evaluation
- R² Score
- Root Mean Squared Error (RMSE)
- Actual vs Predicted Analysis
- Residual Diagnostics

## 📊 Linear Regression Model Performance

| Evaluation Metric | Training | Testing |
|---|---:|---:|
| R² Score | 94.03% | 94.73% |
| RMSE | 6766.35 | 6607.19 |

**Key Result:** The Linear Regression model achieved a test R² score of approximately 94.73%.

The statistical diagnostic tests also identified heteroscedasticity and non-normal residuals, which are important limitations to consider when interpreting the model.

## 💡 Key Learnings

- Data cleaning and preprocessing
- Exploratory Data Analysis
- Feature engineering
- Statistical hypothesis testing
- Multicollinearity analysis
- Regression modelling
- Model evaluation and diagnostics

## 🚀 Future Improvements

- Hyperparameter tuning
- Cross-validation
- Pipeline implementation
- Model performance comparison
- Further improvement in prediction accuracy

## 👨‍💻 Author

**Anoop Verma**

Aspiring Data Analyst | Machine Learning Enthusiast

## ⭐ Conclusion

This project demonstrates an end-to-end machine learning workflow, from raw data analysis and preprocessing to regression modelling and evaluation.

It helped develop practical understanding of data analysis, statistical techniques, and predictive modelling.
