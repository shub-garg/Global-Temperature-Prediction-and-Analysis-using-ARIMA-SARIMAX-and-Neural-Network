# Climate Analysis and Prediction Project

## Overview
Investigating temperature changes over time and predicting future temperature patterns regionally and globally stands as the central challenge of this project. To accomplish this, we will employ time series forecasting methods such as neural networks, ARIMA and SARIMAX on the GISTEMP v4 dataset from NASA.

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
- **global_temp_nn/**: Jupyter notebooks for data exploration, cleaning, analysis, and Neural Network.
- **arima_sarima/**: Jupyter notebooks for ARIMA and SARIMAX Time Series Forecasting.
- **images/**: Contains images generated during the analysis.
- **data/**: Dataset files used in the project.
- **README.md**: Project overview and instructions.
- **'video.avi'**: Temperature Anomalies plotted on world map from 1880 to 2023


## Data
The dataset used in this project includes:
- Global Surface Temperatures
- Northern Hemisphere Temperatures
- Southern Hemisphere Temperatures
- Zonal Temperatures
- Extended Reconstruction SSTs Version 5 (ERSSTv5) (NetCDF file)

## Analysis and Modeling
- **Exploratory Data Analysis (EDA)**: Initial exploration of the dataset to understand patterns and trends.
- *Data Cleaning*: Handling missing values, interpolation, and ensuring data integrity.
- *Time Series Forecasting*: Utilizing ARIMA and SARIMAX for time series forecasting.
- *Neural Network Models*: Implementing neural networks for more complex analyses.

## How to Run
Download the zip file and run the individual Jupyter notebooks:
1. global_temp_nn.inpy
2. arima_sarimax.inpy

## Dependencies
Tensorflow 
Statsmodel

## Contributing
Shubham Garg- sg8311@nyu.edu
Raunak Shukla - rs8668@nyu.edu
Phani Varma Gadiraju - pg2542@nyu.edu

## License
This project is licensed under the [MIT License](LICENSE).
