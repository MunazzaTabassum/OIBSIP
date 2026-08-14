# House Price Prediction using Linear Regression

## Project Overview

This project focuses on predicting house prices using Linear Regression. The analysis covers data inspection, preprocessing, feature selection, exploratory analysis, model training, evaluation, and interpretation.

The project demonstrates an end-to-end machine learning workflow using Python and scikit-learn.

## Objective

Build and evaluate a Linear Regression model to predict house prices based on property characteristics such as area, number of bedrooms, bathrooms, stories, parking, and other housing features.

## Dataset

The dataset contains housing property information including:

- Price
- Area
- Bedrooms
- Bathrooms
- Stories
- Mainroad
- Guestroom
- Basement
- Hot Water Heating
- Air Conditioning
- Parking
- Preferred Area
- Furnishing Status

The dataset contains 545 records and 13 columns.

## Project Workflow

1. Loaded and inspected the dataset
2. Checked data types and dataset structure
3. Checked for missing values
4. Checked for duplicate records
5. Generated descriptive statistics
6. Analyzed the distribution of house prices
7. Selected relevant numerical and categorical features
8. Analyzed feature correlations using a heatmap
9. Encoded categorical variables using One-Hot Encoding
10. Split the data into 80% training and 20% testing sets
11. Built a preprocessing and Linear Regression pipeline
12. Trained the Linear Regression model
13. Generated predictions on test data
14. Evaluated the model using MSE, RMSE, and R²
15. Visualized actual versus predicted prices
16. Created a residual plot
17. Analyzed model coefficients to identify influential features

## Model Evaluation

The Linear Regression model achieved the following results on the test dataset:

- Mean Squared Error (MSE): 1,754,318,687,330.67
- Root Mean Squared Error (RMSE): 1,324,586.96
- R² Score: 0.6529

The R² score indicates that the model explains approximately 65.29% of the variation in house prices in the test dataset.

## Key Findings

- Area and number of bathrooms were among the strongest numerical factors influencing predicted house prices.
- Features such as air conditioning, number of stories, hot water heating, preferred area, and furnishing status also contributed to the model.
- The actual-versus-predicted visualization shows a positive relationship between actual and predicted house prices.
- The residual plot was used to examine the distribution of prediction errors around zero.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Structure

```text
DataAnalytics-L2-Task1-HousePricePrediction/
│
├── dataset/
│   └── Housing.csv
│
├── notebooks/
│   └── House_Price_Prediction.ipynb
│
├── outputs/
│   ├── price_distribution.png
│   ├── correlation_heatmap.png
│   ├── actual_vs_predicted.png
│   └── residual_plot.png
│
├── README.md
└── requirements.txt


Conclusion

This project demonstrates a complete machine learning workflow for house price prediction, from data preprocessing and exploratory analysis to model development, evaluation, visualization, and interpretation.



