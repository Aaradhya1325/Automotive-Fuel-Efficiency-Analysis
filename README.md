
# Automotive Fuel Efficiency Analysis and Prediction Using Python

## Project Overview
This project analyses historical automobile data to understand the factors affecting vehicle fuel efficiency and builds a machine learning model to predict fuel consumption efficiency in miles per gallon (MPG).

The project uses the Auto MPG dataset from the UCI Machine Learning Repository, containing 398 vehicle records.

## Objectives
- Analyse the relationship between vehicle specifications and fuel efficiency.
- Identify the key factors influencing MPG.
- Perform data cleaning and exploratory data analysis.
- Build a Linear Regression model to predict vehicle fuel efficiency.
- Evaluate model performance using standard regression metrics.

## Dataset
**Source:** UCI Machine Learning Repository – Auto MPG Dataset

https://archive.ics.uci.edu/dataset/9/auto+mpg

The dataset includes:
- Cylinders
- Displacement
- Horsepower
- Weight
- Acceleration
- Model year
- Origin
- Miles per gallon (MPG) – prediction target

## Tools and Technologies
- Python
- Google Colab
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Linear Regression

## Methodology
1. Data collection and loading.
2. Data inspection and preprocessing.
3. Handling missing horsepower values using median imputation.
4. Exploratory Data Analysis (EDA).
5. Correlation analysis and data visualisation.
6. Model development using Linear Regression.
7. Model evaluation using regression metrics.

## Key Findings
- Vehicle weight has a strong negative correlation with MPG (-0.83).
- Horsepower also has a strong negative correlation with MPG (-0.78).
- Vehicle weight and horsepower show a strong positive correlation (+0.86).

## Model Performance
The Linear Regression pipeline achieved the following results on the test dataset:

| Evaluation Metric | Result |
|---|---:|
| MAE | 2.29 |
| MSE | 8.34 |
| RMSE | 2.89 |
| R² Score | 0.845 |

The R² score indicates that the model explains approximately 84.5% of the variation in MPG in the test dataset.

## Project Files
- `Copy_of_Automotive_Fuel_Efficiency_Analysis_Week1.ipynb` – Python notebook containing the analysis, visualisations and machine learning model.

## Limitations
The Auto MPG dataset contains historical vehicle records. Therefore, the findings and model predictions may not directly represent the fuel efficiency of modern vehicles or electric vehicles.

## Conclusion
This project demonstrates how Python and machine learning can be used to analyse automotive data, identify important factors affecting fuel efficiency and develop a predictive model.

---
**Project Domain:** Automotive Data Analytics  
**Project Area:** Data Science and Predictive Analytics  
**Role:** Automotive Data Analyst Intern
