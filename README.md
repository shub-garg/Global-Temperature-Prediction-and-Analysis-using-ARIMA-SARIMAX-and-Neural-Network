# Global Temperature Prediction and Analysis

## Overview
This project aims to investigate temperature changes over time and predict future temperature patterns on a regional and global scale. We employ time series forecasting methods, including neural networks, ARIMA, and SARIMAX, using the GISTEMP v4 dataset from NASA.

## Table of Contents
- [Project Structure](#project-structure)
- [Data](#data)
- [Analysis and Modeling](#analysis-and-modeling)
- [Results](#results)
- [How to Run](#how-to-run)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Project Structure
- **global_temp_nn/**: Jupyter notebooks for data exploration, cleaning, analysis, and neural network implementation.
- **arima_sarima/**: Jupyter notebooks for ARIMA and SARIMAX time series forecasting.
- **images/**: Contains images generated during the analysis.
- **data/**: Dataset files used in the project.
- **README.md**: Project overview and instructions.
- **temperature_video_june.avi**: Temperature anomalies plotted on a world map from 1880 to 2023.

## Video

![temperature_video_june](https://github.com/shub-garg/Global-Temperature-Prediction-and-Analysis-using-ARIMA-SARIMAX-and-Neural-Network/assets/52582943/ed3d12a1-6545-4df3-84e7-a5ddce9e47c0)

## Data
The dataset used in this project includes:

- Global Surface Temperatures
- Northern Hemisphere Temperatures
- Southern Hemisphere Temperatures
- Zonal Temperatures
- Extended Reconstruction SSTs Version 5 (ERSSTv5) (NetCDF file)

## Analysis and Modeling
- **Exploratory Data Analysis (EDA)**: Initial exploration of the dataset to understand patterns and trends.
- **Data Cleaning**: Handling missing values, interpolation, and ensuring data integrity.
- **Time Series Forecasting**: Utilizing ARIMA and SARIMAX for time series forecasting.
- **Neural Network Models**: Implementing neural networks for more complex analyses.

## Results
- Visualizations of temperature anomalies over time.
- Forecasts of future temperature trends using ARIMA and SARIMAX.
- Neural network predictions for complex analysis of temperature patterns.

## How to Run
Download the zip file and run the individual Jupyter notebooks:
1. `global_temp_nn.ipynb`
2. `arima_sarimax.ipynb`

## Dependencies
- TensorFlow
- Statsmodels

Install the required packages using:
```bash
pip install tensorflow statsmodels
```

## Contributing
Shubham Garg- sg8311@nyu.edu
Raunak Shukla - rs8668@nyu.edu
Phani Varma Gadiraju - pg2542@nyu.edu

## License
This project is licensed under the [MIT License](LICENSE).
