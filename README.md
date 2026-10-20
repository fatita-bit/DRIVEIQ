# DRIVEIQ — Car Rental Price Prediction

## Project Overview

DRIVEIQ is a machine learning project that estimates car rental prices based on rental duration, vehicle brand, and season.

The project uses a **Random Forest Regressor** implemented with Python and Scikit-learn, along with an interactive interface built using Gradio.

## Features

- Estimate a car rental price based on selected input features.
- Visualize estimated prices across rental durations.
- Compare estimated prices across different car brands.
- Display model evaluation metrics.

## Technologies

- Python
- Pandas and NumPy
- Scikit-learn
- Matplotlib
- Gradio
- Machine Learning — Random Forest Regression

## Dataset

**Important:** This project uses a synthetic dataset generated for educational and demonstration purposes. It does not contain real car rental market prices.

Consequently, the evaluation metrics reflect performance on synthetic data and should not be interpreted as evidence of accuracy on real-world rental prices.

## Model Evaluation

The model was evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- Coefficient of Determination (R²)

The reported metrics are based on the synthetic dataset.

## How to Run

1. Clone or download this repository.
2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter notebook `prediction_prix_location_voitures.ipynb`.
4. Run the notebook cells in order.

## Author

Created as a personal machine learning project to practice regression, model evaluation, and interactive application development.
