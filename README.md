## COVID-19 State-Wise Analysis (India)

## Project Overview
This is a beginner-friendly data science project analyzing COVID-19 state-wise data in India. 
The project covers data cleaning, exploratory data analysis (EDA), visualization, and machine learning models to predict total COVID-19 cases.

## Objectives
- Clean and preprocess state-wise COVID-19 data
- Explore patterns and trends using visualizations
- Identify top states by total cases and death ratio
- Predict total cases using machine learning algorithms

## Key Features
- **Data Cleaning:** Handled missing values, removed unnecessary rows, and converted numeric columns
- **Feature Engineering:** Created `Cases_per_100k` and `Deaths_per_100k` to normalize data by population
- **Data Visualization:** 
  - Bar Chart (Top 10 States by Death Ratio)
  - Pie Chart (Share of Death Ratio)
  - Line Chart (Trend across top states)
  - Scatter Plot (Death Ratio vs Total Cases)
  - Area Chart (Death Ratio trend)
  - Heatmap (Correlation among numeric features)
  - Combined Bar + Line chart (Total Cases vs Death Ratio)
- **Machine Learning Models:** 
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
- **Model Evaluation:** R² Score, RMSE, and comparison of model performance

## Technologies & Libraries Used
- Python
- Pandas
- Numpy
- Matplotlib & Seaborn
- Scikit-learn

## How to Use
1. Clone this repository
2. Place the CSV file (`covid_data.csv`) in the project folder
3. Open the Jupyter Notebook and run each cell step by step
4. Explore visualizations and ML model results

## Project Insights
- Random Forest gave the best predictive accuracy for total cases
- States with higher populations tend to have more total cases, but death ratios vary
- Visualizations help identify trends and patterns easily

## CV-Ready Summary
Developed a COVID-19 state-wise analysis project using Python, Pandas, Seaborn, and ML models (Linear Regression, Decision Tree, Random Forest). 
Performed data cleaning, visualization, and prediction of total cases with high accuracy.


Visualization helps identify patterns and trends easily.
