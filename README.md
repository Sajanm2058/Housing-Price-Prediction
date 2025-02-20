# Housing Price Prediction using Linear Regression

## Overview
This project implements a Linear Regression model to predict housing prices using the Boston Housing dataset. It includes data preprocessing, model training, evaluation, and visualization.

## Dataset
The dataset consists of various features related to housing data, such as crime rate, number of rooms, tax rate, and others. The target variable is `MEDV`, which represents the median house price.

## Features
The dataset contains the following columns:
- `CRIM`: Crime rate per capita
- `ZN`: Proportion of residential land zoned for large lots
- `INDUS`: Proportion of non-retail business acres per town
- `CHAS`: Charles River dummy variable (1 if tract bounds river, 0 otherwise)
- `NOX`: Nitrogen oxide concentration
- `RM`: Average number of rooms per dwelling
- `AGE`: Proportion of owner-occupied units built before 1940
- `DIS`: Weighted distances to employment centers
- `RAD`: Index of accessibility to highways
- `TAX`: Property tax rate
- `PTRATIO`: Pupil-teacher ratio
- `B`: Proportion of Black residents
- `LSTAT`: Percentage of lower status population
- `MEDV`: Median house price (Target variable)

## Installation
To run this project, install the required Python libraries:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage
Run the Python script to train the model and visualize results:
```bash
python housing_price_lr.py
```

## Visualizations
The script includes:
- A correlation heatmap to analyze feature relationships
- A pair plot of selected features
- A scatter plot of actual vs. predicted prices
- A histogram of prediction errors

## Model Evaluation Metrics
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**

## License
This project is for educational purposes and follows an open-source license.

## Author
Sajan Maharjan

