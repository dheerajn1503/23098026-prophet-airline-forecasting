# Time Series Forecasting with Facebook Prophet

This tutorial demonstrates how to use Facebook Prophet for time series forecasting using the classic International Airline Passengers dataset. The project includes steps for exploratory data analysis (EDA), model fitting, forecasting future data points, and visualizing trends and seasonal components.

## Files Included

- final_prophet_airline_forecast_tutorial.ipynb: Jupyter Notebook with full tutorial and visuals
- README.md: Overview and setup instructions
- requirements.txt: List of Python dependencies required to run the notebook

## Dataset

The dataset used is the Monthly International Airline Passengers dataset (1949–1960), available via a public GitHub repository:  
https://raw.githubusercontent.com/jbrownlee/Datasets/master/airline-passengers.csv

## Learning Objectives

- Perform EDA on time series data to identify trends and seasonality
- Format data appropriately for Prophet
- Train a Prophet model to forecast future values
- Visualize both overall forecasts and model components (trend, seasonality)

## Setup Instructions

1. Clone the repository or download the project files  
2. Install the dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Launch the Jupyter Notebook:
   ```
   jupyter notebook final_prophet_airline_forecast_tutorial.ipynb
   ```

## References

- Taylor, S. J., & Letham, B. (2018). Forecasting at scale. The American Statistician, 72(1), 37–45. https://doi.org/10.1080/00031305.2017.1380080  
- Prophet Documentation: https://facebook.github.io/prophet/docs/quick_start.html  
- Airline Passengers Dataset: https://raw.githubusercontent.com/jbrownlee/Datasets/master/airline-passengers.csv

## License

MIT License
