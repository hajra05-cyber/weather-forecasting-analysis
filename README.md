# Weather Forecasting Using Machine Learning

## Project Overview

This project analyses a global weather dataset using Python. The workflow includes data cleaning, exploratory data analysis (EDA), geographical analysis, and temperature forecasting using machine learning models.

## Objectives

- Clean and preprocess the dataset
- Perform exploratory data analysis
- Explore geographical weather patterns
- Build temperature forecasting models
- Compare forecasting performance
- Develop an ensemble forecasting model

## Dataset

The dataset contains global weather observations, including:

- Temperature
- Humidity
- Wind speed
- Atmospheric pressure
- Visibility
- UV Index
- Air Quality
- Latitude and Longitude
- Date and Time

## Methodology

1. Data cleaning
2. Exploratory Data Analysis
3. Geographical analysis
4. Baseline forecasting model
5. Random Forest model
6. XGBoost model
7. Ensemble model
8. Model evaluation using MAE, RMSE and R²

## Results

| Model | MAE | RMSE | R² |
|------|------:|------:|------:|
| Baseline | 7.72 | 10.44 | -0.361 |
| Random Forest | 2.28 | 3.22 | 0.870 |
| XGBoost | 2.33 | 3.19 | 0.873 |
| Ensemble | **2.16** | **3.00** | **0.887** |

The ensemble model achieved the best forecasting performance.

## Files

- Weather Forcasting Code.ipynb
- Weather Trend Forecasting Report.pdf
- weather_forecasting_cleaned_dataset.zipped
- README.md

**Note:** The original dataset is not included because it exceeds GitHub's file size limit. The dataset is available on the Kaggle website. 
World Weather Repository: https://www.kaggle.com/datasets/nelgiriyewithana/global-weather-repository/code


## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost
- GitHub

## Author

Your Name
