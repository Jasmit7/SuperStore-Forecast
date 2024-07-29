
---

# Time Series Forecasting on Superstore Data

This project focuses on time series analysis and forecasting for Superstore sales data, specifically targeting the furniture category. The goal is to predict future sales using various time series models.

## Project Structure

- **Data Preprocessing**: Cleaning and preparing the data for analysis.
- **Exploratory Data Analysis (EDA)**: Visualizing sales trends and patterns.
- **Time Series Decomposition**: Breaking down the series into trend, seasonality, and noise[^1^][1].
- **Modeling**: Implementing ARIMA and Prophet models for forecasting.
- **Validation**: Comparing model predictions with actual sales data.
- **Forecasting**: Generating future sales forecasts and visualizing them.

## Requirements

- Python 3.9
- Libraries: TensorFlow, NumPy, Pandas, Matplotlib, Statsmodels, Prophet

## Usage

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Jasmit7/SuperStore-Forecast
   cd SuperStore-Forecast
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```

4. **Execute the cells in the notebook** to preprocess data, perform EDA, build models, and generate forecasts.

## Results

- **ARIMA Model**: Captured seasonality and trend with a Mean Squared Error (MSE) of 22993.57.
- **Prophet Model**: Provided robust forecasts with clear seasonal patterns.

## Conclusion

The models effectively forecasted furniture sales, demonstrating the potential for accurate time series predictions in retail data.

---

