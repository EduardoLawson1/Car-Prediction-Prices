# Car Price Prediction

This project is focused on predicting car prices using various machine learning models. The dataset used in this project is sourced from Kaggle, and the models implemented include:

- **XGBRegressor**
- **Linear Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**

## Dataset

The dataset used for this project is the [Car Price Prediction dataset](https://www.kaggle.com/datasets) available on Kaggle. The dataset contains various features related to cars, such as:

- **Make and Model**
- **Year of Manufacture**
- **Engine Size**
- **Mileage**
- **Fuel Type**
- **Transmission**
- **Number of Owners**
- **Price**

## Models Implemented

### 1. **XGBRegressor**

- **Description**: XGBRegressor is an implementation of gradient boosting focused on speed and performance.
- **Metrics**: Mean Absolute Error (MAE), R-squared (R2)

### 2. **Linear Regression**

- **Description**: A simple regression model that assumes a linear relationship between the input features and the target variable.
- **Metrics**: Mean Absolute Error (MAE), R-squared (R2)

### 3. **Decision Tree Regressor**

- **Description**: A model that predicts the target by learning simple decision rules inferred from the data features.
- **Metrics**: Mean Absolute Error (MAE), R-squared (R2)

### 4. **Random Forest Regressor**

- **Description**: An ensemble learning method that constructs multiple decision trees during training and outputs the average prediction.
- **Metrics**: Mean Absolute Error (MAE), R-squared (R2)

## Results

After training the models, the performance was evaluated using the test set. Below are the key results:

- **XGBRegressor**: MSE = `1491.66`, R2 = `0.93`
- **Linear Regression**: MSE = `2278.82`, R2 = `0.83`
- **Decision Tree Regressor**: MSE = `1853.27`, R2 = `0.90`
- **Random Forest Regressor**: MSE = `1289.26`, R2 = `0.95`


## Visualization

The predictions of all models were visualized and compared in a single plot. This helps in understanding how each model performs relative to the actual car prices.
