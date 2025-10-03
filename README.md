# Forecasting-Analysing-Climate-Parameters-of-Kashmir-valley-using-ARIMA-Model
Project Overview

This project aims to analyze and forecast key climate parameters in the Kashmir valley using the Autoregressive Integrated Moving Average (ARIMA) model. By leveraging over a century's worth of historical climate data, from 1901 to 2019, this analysis seeks to uncover trends and predict future changes in temperature, precipitation, and cloud cover. Understanding these patterns is crucial for addressing the impacts of climate change on the region's unique ecosystem and economy, which are heavily reliant on agriculture and tourism. The Kashmir valley, known for its distinct seasons—spring, summer, autumn, and winter—has been experiencing noticeable shifts in its climate, including changes in snowfall patterns and rising temperatures. This project provides a data-driven approach to understanding these changes and their potential implications.

Key Objectives
Analyze Historical Trends: To examine long-term trends in climate data to identify significant shifts over the past century.

Develop Forecasting Models: To build and validate ARIMA models for predicting future climate patterns.

Evaluate Model Performance: To assess the accuracy of the models using metrics such as Root Mean Squared Error (RMSE).

Dataset

The data used in this project is from the CRU TS4.04 dataset, provided by the Climatic Research Unit at the University of East Anglia. This high-resolution gridded dataset contains monthly time-series data for various climate variables from 1901 to 2019. The key parameters analyzed in this project include:
Mean Temperature (tmp): Average monthly temperature.
Precipitation (pre): Total monthly precipitation.
Cloud Cover (cld): Percentage of cloud cover.

Methodology

The project follows a structured approach to time-series analysis and forecasting:

Data Cleaning and Preprocessing: The raw data is cleaned to handle inconsistencies and format it for analysis. This includes restructuring the dataset to create a proper time-series format.

Exploratory Data Analysis (EDA): Before modeling, the time-series data is analyzed to check for stationarity using the Augmented Dickey-Fuller (ADF) test. The Autocorrelation Function (ACF) and Partial Autocorrelation Function (PACF) plots are also examined to determine the optimal parameters for the ARIMA model.

ARIMA Modeling: The ARIMA model is implemented with the identified parameters (p,d,q) to forecast future climate trends. The model is trained on a subset of the data and validated on the remaining portion to ensure its predictive accuracy.

Results and Evaluation: The model's performance is evaluated by comparing the forecasted values with the actual data. The final results are visualized to illustrate the projected climate trends for the Kashmir valley.
