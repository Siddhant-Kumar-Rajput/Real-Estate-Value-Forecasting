# Real Estate Value Forecasting

## Project Overview

"Real Estate Value Forecasting" is a predictive data analysis project aimed at estimating house prices using machine learning techniques. This project involves data cleaning, visualization, and the application of a linear regression model for prediction.

## Dataset

The dataset used for this project was sourced from Kaggle and is saved as `Pricing_Data.csv`.

## Files and Directories

- `Pricing_Data.csv`: The original dataset downloaded from Kaggle.
- `Pricing_DataCleaning.ipynb`: Jupyter Notebook for data cleaning processes.
- `Cleaned_Data_Pricing.csv`: The cleaned dataset after preprocessing.
- `Pricing_DataVisual.ipynb`: Jupyter Notebook for data visualization using Matplotlib and Seaborn.
- `Pricing_DataModel.ipynb`: Jupyter Notebook for predicting house prices using a linear regression model.

## Data Cleaning Process

The data cleaning process was performed in `Pricing_DataCleaning.ipynb` and included the following steps:
1. **Detecting Null Values**: Identified missing values in the dataset.
2. **Handling Null Values**: Filled or removed null values as appropriate.
3. **Data Type Updates**: Ensured all data types were correctly formatted.
4. **Dropping Irrelevant Columns**: Removed unnecessary columns that did not contribute to the analysis.

The cleaned data was saved as `Cleaned_Data.csv`.

## Data Visualization

Data visualization was conducted in `Pricing_DataVisual.ipynb` using the following libraries:
- **Matplotlib**: For creating static, interactive, and animated visualizations.
- **Seaborn**: For making statistical graphics.

These visualizations helped in understanding the distribution and relationships within the dataset.

## Model Building

The predictive model was developed in `Pricing_DataModel.ipynb` using:
- **Linear Regression**: Applied a simple linear regression model to predict house prices.
- **Model Evaluation**: Achieved a perfect score of 1.0, indicative of a small and well-fitted dataset.
