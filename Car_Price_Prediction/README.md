
# Car Price Prediction with Machine Learning

This project uses machine learning models to predict the price of cars based on several factors like the car's brand, mileage, horsepower, fuel type, and more.

## Project Overview

The objective of this project is to build a predictive model that estimates the price of a used car based on various features such as:

- Year of manufacturing
- Brand of the car
- Mileage
- Fuel type
- Transmission type
- And more...

### Models Used:
1. Random Forest Regressor
2. Linear Regression

The dataset contains details of various cars, and both Random Forest and Linear Regression models were used to predict their prices. The model with the best performance was chosen for predictions.

## Files in this Repository

1. **`car_data.csv`** - The dataset containing the details of various cars used to train the machine learning models.
2. **`car_price_random_forest_model.pkl`** - The trained Random Forest Regressor model.
3. **`car_price_linear_regression_model.pkl`** - The trained Linear Regression model.
4. **`car_price_predictor.py`** - Python script for building, training, and testing the machine learning models.
5. **`README.md`** - This file.

## Setup & Installation

1. Clone this repository to your local machine:
    ```bash
    git clone <repository-url>
    ```

2. Navigate to the project directory:
    ```bash
    cd <repository-directory>
    ```

3. Install the required Python libraries:
    ```bash
    pip install -r requirements.txt
    ```

4. Place the dataset (`car_data.csv`) in the appropriate directory.

5. Load the trained models using the `joblib` or `pickle` libraries.

## Usage

1. To make predictions using the trained model:
    ```python
    from car_price_predictor import predict_price
    
    model = 'random_forest'  # or 'linear_regression'
    features = [year, present_price, driven_kms, fuel_type, transmission_type, owner, brand]
    predicted_price = predict_price(features, model)
    print(f"Predicted Price: {predicted_price}")
    ```

2. Alternatively, you can load the model and dataset from the command line.

## Contributing

If you'd like to contribute to this project, feel free to fork the repository, create a branch, and submit a pull request.

## License

This project is open source and available under the MIT License.

