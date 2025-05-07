# Car Price Prediction with Machine Learning

This project uses machine learning models to predict the price of cars based on several factors like the car's brand, mileage, engine size, fuel type, transmission type, and more.

## Project Overview

The objective of this project is to build a predictive system that estimates the selling price of a used car based on various features such as:

* Year of manufacturing
* Present Price
* Driven Kilometers
* Number of Owners
* Brand (encoded)
* Fuel Type (encoded)
* Selling Type (encoded)
* Transmission Type (encoded)

Users can interact with the system, input their car's details, and receive an estimated price prediction instantly.

### Models Used:

1. Random Forest Regressor
2. Linear Regression

The dataset includes various features of cars, and both Random Forest and Linear Regression models were trained to predict their prices. Users can select either model while making predictions.

## Files in this Repository

1. **`car_data.csv`** - The dataset containing the car details used to train the machine learning models.
2. **`car_price_random_forest_model.pkl`** - The trained Random Forest Regressor model.
3. **`car_price_linear_regression_model.pkl`** - The trained Linear Regression model.
4. **`car_price_predictor.py`** - Python script for user input, model selection, and prediction.
5. **`Car_Price_Prediction.ipynb`** - Jupyter notebook for model training, evaluation, and saving.
6. **`README.md`** - This file.

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

4. Ensure you have the dataset (`car_data.csv`) and model files (`.pkl`) in the correct locations.

5. Run the Python script or Jupyter notebook as needed.

## Usage

1. To make a prediction:

   * Run the Python script `car_price_predictor.py`.
   * Choose which model to use (Random Forest or Linear Regression).
   * Enter the car details as prompted.
   * Receive the predicted car price.

2. Example snippet if calling prediction function directly:

   ```python
   from car_price_predictor import predict_price

   model = 'random_forest'  # or 'linear_regression'
   features = [year, present_price, driven_kms, owner, brand_encoded, fuel_type_encoded, selling_type_encoded, transmission_encoded]
   predicted_price = predict_price(features, model)
   print(f"Predicted Price: ₹{predicted_price:.2f} Lakhs")
   ```

## Contributing

If you'd like to contribute to this project, feel free to fork the repository, create a branch, and submit a pull request.

## License

This project is open source and available under the MIT License.
