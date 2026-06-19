#  House Price Prediction using Machine Learning

##  Project Overview

This project predicts residential property prices using Machine Learning techniques based on property attributes such as area, number of bedrooms, bathrooms, floors, location, condition, garage availability, and construction year.

The project includes complete data preprocessing, exploratory data analysis (EDA), feature engineering, model training, performance evaluation, and visualization. Two regression models were implemented and compared:

* Linear Regression
* Gradient Boosting Regressor

The objective is to identify the model that provides the most accurate house price predictions while understanding the factors that influence property valuation.

---

## Key Features

 Data Cleaning & Preprocessing

Missing Value Handling

Outlier Detection & Removal

Exploratory Data Analysis (EDA)

Feature Scaling & Encoding

 Linear Regression Model

 Gradient Boosting Regressor

 Model Performance Comparison

 Feature Importance Analysis

 Actual vs Predicted Visualization

 Residual Analysis

---

##  Dataset

**Dataset:** House Price Prediction Dataset (Kaggle)

### Features

| Feature   | Description               |
| --------- | ------------------------- |
| Area      | House area in square feet |
| Bedrooms  | Number of bedrooms        |
| Bathrooms | Number of bathrooms       |
| Floors    | Number of floors          |
| YearBuilt | Construction year         |
| Location  | Property location         |
| Condition | Property condition        |
| Garage    | Garage availability       |
| Price     | Target variable           |

---

## Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

### Machine Learning Models

* Linear Regression
* Gradient Boosting Regressor

### Evaluation Metrics

* MAE (Mean Absolute Error)
* RMSE (Root Mean Squared Error)
* R² Score

---

##  Project Workflow

### 1. Data Loading

* Import housing dataset
* Inspect dataset structure

### 2. Data Cleaning

* Handle missing values
* Remove duplicate records
* Filter extreme outliers

### 3. Exploratory Data Analysis

* Price distribution analysis
* Correlation analysis
* Feature relationship visualization

### 4. Feature Engineering

* Numerical feature scaling
* One-Hot Encoding for categorical variables

### 5. Model Training

* Linear Regression
* Gradient Boosting Regressor

### 6. Model Evaluation

* MAE
* RMSE
* R² Score

### 7. Visualization

* Actual vs Predicted Comparison
* Error Analysis
* Residual Distribution
* Feature Importance

---

## Model Evaluation Metrics

### Mean Absolute Error (MAE)

Measures the average prediction error.

**Lower MAE = Better Performance**

---

### Root Mean Squared Error (RMSE)

Penalizes large prediction errors more heavily.

**Lower RMSE = Better Performance**

---

### R² Score

Measures how much variance in house prices is explained by the model.

**Higher R² = Better Performance**

---

##  Generated Visualizations

The project automatically generates:

### EDA Dashboard

* Price Distribution
* Price vs Area
* Price by Bedrooms
* Correlation Heatmap
 

### Model Evaluation Dashboard

* Actual vs Predicted (Linear Regression)
* Actual vs Predicted (Gradient Boosting)
* Error Comparison
* Residual Analysis

 

### Feature Importance Analysis

Displays the most influential features affecting house prices.

 
---

##  Results

The project compares both regression models and identifies the best-performing model based on:

* Lowest MAE
* Lowest RMSE
* Highest R² Score

In most cases, **Gradient Boosting Regressor** outperforms Linear Regression because it captures complex non-linear relationships between housing features and price.

---

 
##  Learning Outcomes

Through this project, I gained practical experience in:

* Data Cleaning & Preparation
* Exploratory Data Analysis
* Feature Engineering
* Machine Learning Pipelines
* Regression Modeling
* Model Evaluation
* Data Visualization
* Business-Oriented Predictive Analytics

---

##  Author

**Tooba Fatima**

Artificial Intelligence Student | Machine Learning Enthusiast

GitHub: https://github.com/toobafatima21ai-hue

LinkedIn: https://www.linkedin.com/in/tooba-fatima

---

⭐ If you found this project useful, consider giving it a star on GitHub.
