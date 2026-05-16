# BAN644-BigMart-Sales-Prediction Using Machine Learning

## Project Overview

This project was developed for the course BAN644/BAN744: Applied Machine Learning for Business Analytics with Python.

The objective of this project is to predict retail product sales using machine learning algorithms and generate business insights that can support better retail decision-making.

This is a regression-based machine learning project where the target variable is:

Item_Outlet_Sales

---

## Business Problem

Retail businesses need accurate sales forecasting to:

- Improve inventory management
- Reduce product shortages
- Optimize promotions
- Increase profitability
- Support business planning

This project aims to forecast sales using historical BigMart retail data.

---

## Dataset Information

Dataset Name:
BigMart Sales Dataset

Dataset Source:
https://www.kaggle.com/datasets/brijbhushannanda1979/bigmart-sales-data

Files Used:
- Train.csv

Target Variable:
- Item_Outlet_Sales

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Machine Learning Algorithms Used

1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor

---

## Project Workflow

1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Feature Selection
6. Model Building
7. Model Evaluation
8. Hyperparameter Tuning
9. Business Insights & Recommendations

---

## Data Preprocessing Steps

- Handled missing values
- Removed duplicates
- Fixed inconsistent categorical labels
- Encoded categorical variables
- Created new features such as Outlet_Age

---

## Exploratory Data Analysis (EDA)

The following analyses were performed:

- Sales distribution analysis
- Product category analysis
- Outlet type comparison
- Correlation heatmap
- Fat content analysis

---

## Model Evaluation Metrics

The following regression metrics were used:

- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score

---

## Best Performing Model

Random Forest Regressor achieved the best performance among all models because it handled nonlinear relationships effectively and produced higher prediction accuracy.

---

## Business Insights

- Supermarket outlets generated higher sales.
- Product visibility influenced sales performance.
- Outlet age affected revenue generation.
- Certain product categories consistently achieved stronger sales.

---

## Recommendations

- Increase inventory for high-performing products.
- Improve product visibility strategies.
- Focus marketing on high-performing outlet types.
- Use predictive analytics for better inventory planning.

---

## How to Run the Project

1. Open Google Colab
2. Upload the notebook file
3. Upload Train.csv dataset
4. Run all cells sequentially

---

## Project Structure

BAN644-BigMart-Sales-Prediction/
│
├── BigMart_Sales_Prediction.ipynb
├── README.md
├── dataset/
│   └── Train.csv
└── report/
    └── Final_Report.pdf

---

## Author

Name: Your Name  
Student ID: Your ID  
Course: BAN644/BAN744

---

## AI Usage Disclosure

AI tools such as ChatGPT were used to assist with understanding machine learning concepts, improving coding structure, and debugging Python code. All analysis, interpretation, and conclusions were completed independently by the student.
