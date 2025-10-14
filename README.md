# OIBSIP_PREDICTING-HOUSE-PRICES-WITH-LINEAR-REGERSSION_5

## Project Overview

This project is part of my Oasis Infobyte Data Analytics Internship (Task 5).
The goal of this project is to build a machine learning model that predicts house prices based on various features such as average area income, house age, number of rooms, number of bedrooms, and area population.

House price prediction is a Linear regression problem in Data Analytics that demonstrates how statistical and machine learning techniques can be applied to real-world datasets to make accurate forecasts.
This project strengthened my understanding of Linear Regression, data preprocessing, and model evaluation techniques.

## Objectives

- Data Loading: Load the housing dataset and understand its structure.

- Data Cleaning: Handle missing values, check for duplicates, and ensure consistency.

- Exploratory Data Analysis (EDA): Identify key variables affecting house prices through summary statistics and visualizations.

- Feature Selection: Choose the most relevant features that contribute to price prediction.

- Model Building: Train a Linear Regression model to predict house prices.

- Model Evaluation: Assess model performance using metrics such as R² Score and Mean Squared Error (MSE).

- Visualization: Display relationships between actual and predicted prices using scatter plots and regression coefficient analysis.

## Tools & Technologies Used

Programming Language: Python

Libraries:

- Pandas — for data loading, cleaning, and manipulation

- NumPy — for numerical computation

- Matplotlib & Seaborn — for data visualization

- Scikit-learn — for model training and evaluation

- Environment: Jupyter Notebook

## Project Workflow

- Step 1️ - Data Loading
Loaded the dataset (Housing.csv) into a Pandas DataFrame and inspected it using .info() and .describe() to understand data types, column structure, and missing values.

- Step 2️ - Data Cleaning
- Checked for and confirmed there were no missing or duplicate values.
- Ensured all features were numerical and suitable for regression.
- Dropped unnecessary columns like ‘Address’ since it was non-numeric and irrelevant for prediction.

- Step 3️ - Exploratory Data Analysis (EDA)
- Analyzed the correlation between features and the target variable (Price).
- Used heatmaps and distribution plots to visualize relationships and data trends.
- Identified key predictors such as Average Area Income, House Age, and Area Population that strongly influence house prices.

- Step 4️ - Feature Selection
Selected relevant numerical features:
- Avg. Area Income
- Avg. Area House Age
- Avg. Area Number of Rooms
- Avg. Area Number of Bedrooms
- Area Population
These were used as independent variables to predict the target variable Price.

- Step 5️ - Model Building
- Split the dataset into training (80%) and testing (20%) subsets.
- Trained a Linear Regression model using Scikit-learn’s LinearRegression() class.
- Predicted house prices on the test dataset and compared them with actual values.

- Step 6️ - Model Evaluation
- Evaluated the model using the following metrics:
- R² Score – measures how well the model explains the variance in house prices
- Mean Squared Error (MSE) – quantifies the average squared difference between predicted and actual values
- Visualized Actual vs Predicted Prices using a scatter plot and analyzed regression coefficients to understand feature importance.

## Key Learnings

Through this project, I gained a deeper understanding of:

- Data preprocessing and cleaning techniques

- Correlation analysis and EDA visualization

- Linear Regression implementation and theory

- Model evaluation and performance interpretation

This project demonstrated how data-driven models can assist real estate businesses, buyers, and analysts in making more accurate and informed pricing decisions.

## Files in This Repository

- house.ipynb — Main project notebook

- Housing.csv — Dataset used for training and testing

## Conclusion

The House Price Prediction Project demonstrated how Linear Regression can be effectively applied to real-world datasets for predictive analysis.
By analyzing and preprocessing housing data, training a regression model, and evaluating its performance, I successfully predicted property prices with high accuracy.

This task strengthened my understanding of supervised machine learning, data analysis, and model evaluation, marking another valuable milestone in my Data Analytics internship journey with Oasis Infobyte.
