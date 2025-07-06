# Laptop Price Prediction

Machine learning model to predict laptop prices based on specifications and features.

## Features
* RAM
* Processor
* Storage
* Display Size
* Brand

## Model Details
* Regression model using scikit-learn

## Performance Metrics
* R-Squared
* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE) etc

## Dependencies
* Python 3.x
* scikit-learn
* pandas
* numpy

## Usage
1. Install dependencies: pip install -r requirements.txt
2. Run the script: python predict_laptop_price.py

## Dataset
* https://www.kaggle.com/datasets/aggle6666/laptop-price-prediction-dataset

## Results


✅ Best Params (Raw): {'max_depth': 10, 'min_samples_split': 5, 'n_estimators': 200}



✅ Best Params (Log): {'max_depth': 10, 'min_samples_split': 5, 'n_estimators': 200}

📊 Final Model Evaluation:

🔹 RAW Model Performance:
R²: 0.7244
RMSE: 462.6399
MAE: 304.1584
MAPE: 0.2476

🔹 LOG Model Performance (converted to real scale):
R²: 0.7290
RMSE: 458.7757
MAE: 300.7221
MAPE: 0.2330

## Future Work
* Explore other machine learning models (e.g., decision trees, random forests)
* Collect more data to improve model accuracy

