# TED Talk Views Prediction

This repository contains a machine learning project that focuses on predicting the number of views for TED talks. The project involves data exploration, data cleaning, feature engineering, and the development of regression models using various algorithms. The goal is to build a predictive model that can accurately estimate the views a TED talk will receive.

## Project Overview

TED stands for Technology, Entertainment, and Design. It is an American-Canadian non-profit media organization known for its TED talks, which cover a wide range of topics and are available in multiple languages. This project uses a dataset containing TED talk data collected from 2006 to 2020, with 4,005 observations and 19 features.

## Project Steps

1. **Data Exploration**: In this step, we explore the dataset to gain insights into the data's characteristics. This includes summary statistics, data visualization, and identifying potential patterns and trends.

2. **Data Cleaning**: Data cleaning involves handling missing values, outliers, and any inconsistencies in the dataset to ensure the data is suitable for modeling.

3. **Feature Engineering**: Feature engineering is performed to manipulate and transform the data if needed. It includes creating new features or modifying existing ones to improve model performance.

4. **Model Building**: We build regression models using several algorithms, including:
   - Simple Linear Regression
   - Lasso Regressor
   - RandomForest Regressor
   - XGB Regressor

5. **Model Evaluation**: Model performance is evaluated using various metrics, such as Mean Squared Error (MSE), R-squared (R2), and Adjusted R-squared, to determine the best-performing model.

## Model Performance

Our models are able to predict views with an accuracy rate of approximately 90%. The RandomForest Regressor outperforms other models based on MSE, R2, and Adjusted R2. Notably, the "speaker_wise_avg_views" feature is identified as the most important, indicating a direct impact of speakers on the number of views.

## Libraries Used

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Plotly
- Math
- DateTime
- Scikit-Learn

## Conclusion

This machine learning project successfully predicts TED talk views and provides valuable insights into the factors influencing view counts. The code and detailed analysis can be found in the Jupyter Notebook provided in this repository.

