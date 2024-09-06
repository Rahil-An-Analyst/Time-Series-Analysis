# Project 1: Time Series Forecasting of Share Returns: Model Selection and Prediction for Next 15 Trading Days

## Report
View report here -
(https://rpubs.com/rahil1998/1217012)

## Overview
This project involves analyzing time series data of share returns to identify the best-fitting model among linear, quadratic, cosine, cyclical, and seasonal trend models. The goal is to predict share returns for the next 15 trading days using the best model found.

## Objectives
1. Identify the best-fitting model among linear, quadratic, cosine, cyclical, seasonal trend models or their combinations.
2. Generate predictions for the next 15 trading days using the selected model.

## Data Description
- **Data Source**: assignment1Data2023.csv
- **Columns**:
  - Share Returns: Return in AUD100,000 of a share market trader’s investment portfolio.
- **Observations**: 127 observations out of a possible 252 trading days in a year.

## Plot Inference
- **Seasonality**: Identified as repeating patterns approximately weekly.
- **Trend**: Observed downward trend in mean share returns over time.
- **Change in Variance**: Increasing variance over time, with a greater vertical shift in wave patterns.
- **Behavior**: Mixed behavior with no sudden intervention points.
- **Correlation**: High correlation (0.963) between share returns of consecutive days, indicating consistent behavior between successive trading days.

## Model-Building
The model-building strategy involves:
1. **Model Specification**: Selection of appropriate time series models (linear, quadratic, seasonal, harmonic, or combinations thereof).
2. **Model Fitting**: Estimation of model parameters using least squares statistical techniques.
3. **Model Diagnostics**: Assessment of model fit and verification of modeling assumptions.

## Forecasting
- **Process**:
  1. Generate a sequence of time points for the next 15 trading days.
  2. Use the fitted model to calculate forecasts for these points.
  3. For complex models like Seasonal*Quadratic, use S-ARIMA for forecasting.

- **Forecast Visualization**: 
  - **Blue Lines**: Fitted forecast values for the next 15 trading days.
  - **Shaded Region**: Confidence limits (Lo95 and Hi95) of the forecast values.

## How to Use
- **Setup**: Requires R and necessary packages.
- **Usage**: Run `Time Series Analysis - Project 1.Rmd` in RStudio to generate the analysis report. (Make sure you download and edit the location of the data file in the Rmd before running)

## Files
- `README.md`: This file.
- `Time Series Analysis - Project 1.Rmd`: The R Markdown file with code and analysis.
- `Time-Series-Analysis---Project-1.html`: The HTML report of the analysis.
- `ShareReturns.csv`: The dataset used for time series analysis.

## License
This project is licensed under the MIT License.

## Contact
For more information, please contact [Mohammad Rahil](mailto:smrahil98@gmail.com).
