# House Price Prediction using Linear Regression

This Python script demonstrates how to implement a simple linear regression model to predict house prices based on square footage, number of bedrooms, and number of bathrooms.

## Dependencies

- Python 3.x
- NumPy
- scikit-learn

You can install the dependencies using pip:


## Usage

1. Clone this repository or copy the provided code into your Python environment.
2. Run the script using Python:


## Sample Data

The sample data provided in the script includes the following features:
- Square footage
- Number of bedrooms
- Number of bathrooms

Each feature is paired with the corresponding house price.

## Model Training

The script splits the sample data into training and testing sets using a 80-20 split. It then creates a linear regression model using scikit-learn's `LinearRegression` class and trains it on the training data.

## Evaluation

After training, the model makes predictions on the testing data and calculates the mean squared error (MSE) to evaluate its performance.

## Results

The script prints the following results:
- Mean Squared Error (MSE): A measure of the model's accuracy, lower values indicate better performance.
- Coefficients: The coefficients assigned to each feature by the linear regression model.
- Intercept: The intercept term of the linear regression model.

## Further Improvements

This is a basic implementation of linear regression for house price prediction. Further improvements could include:
- Feature engineering to create more informative features.
- Trying different regression algorithms and comparing their performance.
- Fine-tuning hyperparameters to improve model accuracy.

Feel free to modify and extend the code according to your needs.

