

# House Price Prediction

This project demonstrates a simple linear regression model to predict house prices using the Boston housing dataset. The notebook includes data exploration, visualization, and model training steps.

## Dataset

The dataset used is the Boston housing dataset, which contains information about various attributes of houses in Boston and their corresponding prices.

## Libraries Used

- `numpy`
- `matplotlib`
- `pandas`
- `seaborn`
- `sklearn`

## Steps

1. **Data Loading and Preparation**
    - Load the Boston housing dataset.
    - Convert the dataset into a pandas DataFrame.
    - Add the target variable (house prices) to the DataFrame.

2. **Data Exploration**
    - Display the first few rows of the DataFrame.
    - Check the shape, column names, data types, and unique values.
    - Check for missing values.
    - Generate descriptive statistics.

3. **Data Visualization**
    - Create a heatmap to show correlations between features.
    - Generate pair plots to visualize relationships between features.
    - Create box plots to identify outliers.

4. **Model Training**
    - Split the data into training and testing sets.
    - Train a linear regression model on the training data.
    - Evaluate the model using the testing data.

5. **Model Evaluation**
    - Calculate the model's intercept and coefficients.
    - Predict house prices on the testing set.
    - Evaluate the model's performance using metrics like R² score, mean absolute error, and mean squared error.

## Results

- The model's performance metrics on the testing set are as follows:
    - **R² Score**: [Insert R² Score]
    - **Mean Absolute Error**: [Insert MAE]
    - **Mean Squared Error**: [Insert MSE]

## Files

- `House_price_prediction.ipynb`: The Jupyter notebook containing the code.
- `boston_dataset.csv`: The dataset used for the project.

## How to Run

1. Clone the repository.
2. Install the required libraries.
3. Open the Jupyter notebook and run the cells.

## Conclusion

This project provides a basic example of how to use linear regression for predicting house prices. Further improvements can be made by exploring more advanced models and feature engineering techniques.

