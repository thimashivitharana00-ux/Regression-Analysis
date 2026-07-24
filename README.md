# Real Estate Price Prediction Using Multiple Linear Regression in R

## Overview

This project develops a Multiple Linear Regression model to predict real estate prices using property and location-related features. The analysis includes data preprocessing, exploratory data analysis (EDA), regression modeling, statistical diagnostics, and visualization. The project was implemented in **R** using **R Markdown**, resulting in a reproducible HTML report.

## Objectives

- Explore the housing dataset and understand relationships between variables.
- Identify the key factors affecting real estate prices.
- Develop a Multiple Linear Regression model for price prediction.
- Evaluate the model using statistical measures.
- Verify regression assumptions through diagnostic tests.


## Dataset
This project uses the **Real Estate Price Prediction** dataset available on Kaggle.

**Source:** [Real Estate Price Prediction Dataset (Kaggle)](https://www.kaggle.com/datasets/quantbruce/real-estate-price-prediction)

The dataset includes the following variables:
- Transaction Date
- House Age
- Distance to the Nearest MRT Station
- Number of Nearby Convenience Stores
- Latitude
- Longitude
- House Price per Unit Area

To reproduce this project:

1. Download the dataset from the Kaggle link above.
2. Place the downloaded `Real estate.csv` file in the `data/` folder.
3. Run the R script or R Markdown file.

> **Note:** The dataset is not included in this repository. Please download it directly from Kaggle and follow its license terms.


## Technologies Used

- R
- RStudio
- R Markdown
- ggplot2
- car
- lmtest


## Methodology

The following analytical workflow was performed:

1. Data preprocessing
2. Exploratory Data Analysis (EDA)
3. Multiple Linear Regression
4. Model interpretation
5. Multicollinearity assessment using Variance Inflation Factor (VIF)
6. Normality assessment using the Shapiro–Wilk test
7. Homoscedasticity assessment using the Breusch–Pagan test
8. Residual diagnostics and visualization


## Results

The regression model identified several significant predictors of real estate prices. Diagnostic tests indicated that multicollinearity was low, and additional statistical tests were performed to evaluate model assumptions. The project demonstrates the complete workflow of developing and validating a regression model using R.


## Repository Structure

```
Regression-Analysis/
│
├── code/
│   ├── Regression_Analysis.R
│   └── Regression_Analysis.Rmd
│
├── data/
│   └── https://www.kaggle.com/datasets/quantbruce/real-estate-price-prediction
│
├── output/
│   ├── Regression_Analysis.html
│
Plots/
│   ├── Actual_vs_Predicted.png
│   ├── Residuals_vs_Fitted.png
│   ├── QQ_Plot.png
│   └── (other figures)  
│
├── README.md
├── LICENSE
└── .gitignore
```


## License

This project is licensed under the MIT License.

