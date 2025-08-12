# Crop Yield Time Series Forecasting

This project applies time series forecasting techniques on agricultural crop yield data to predict future yields for different states and seasons. The model can help farmers, researchers, and policymakers plan better and optimize crop production.

## Dataset
The dataset contains crop production details across various states, districts, crops, seasons, and years.

## Features
- State
- District
- Crop
- Year
- Season
- Area
- Production
- Yield

## Methodology
- Data preprocessing (missing value imputation, outlier removal, encoding, scaling)
- Time series decomposition and stationarity checks
- Forecasting using models such as ARIMA/SARIMA/Prophet
- Evaluation using MAE, RMSE, MAPE

## Results
- MAE: 0.0941
- RMSE: 0.1029
- MAPE: 5.48%

## Usage
- Load dataset
- Run preprocessing
- Train and evaluate model
- Visualize forecasts vs actual values

## Requirements
- Python 3.7+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- statsmodels
- prophet

## How to run
1. Clone the repo
2. Install requirements: `pip install -r requirements.txt`
3. Run `notebook.ipynb` or your main script for training and evaluation

---

Feel free to explore and improve the model further!
