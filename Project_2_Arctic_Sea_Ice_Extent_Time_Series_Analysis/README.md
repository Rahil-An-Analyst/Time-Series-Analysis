# Project 2: Arctic Sea Ice Extent Time Series Analysis

## Report
View the detailed report here -
(https://rpubs.com/rahil1998/1217014)

## Overview
This project aims to analyze the Arctic Sea Ice Extent data to identify the best-fitting model for forecasting future trends. The dataset includes observations of Arctic sea ice extent from 1979 to 2022.

## Objectives
- Perform a descriptive analysis of the Arctic Sea Ice Extent data.
- Specify and fit appropriate time series models to the data.
- Evaluate and select the best model based on model scoring techniques.

## Data Description
- **Data Source**: NASA Climate Dataset.
- **Columns**:
  - Year: The year of observation.
  - Sea Ice Extent: The area covered by Arctic Sea ice (in million square kilometers).
- **Observations**: 44 yearly observations from 1979 to 2022.

## Methodology
- **Descriptive Analysis**: Conducted to understand the data characteristics and guide model selection.
- **Model Specification**: Identified potential models including ARIMA and its variants.
- **Model Fitting**: Applied various models to the data and evaluated their performance using AIC, BIC, and error estimation techniques.
- **Model Evaluation**: The ARIMA(1,1,2) model was found to be the best fit based on AIC and BIC scores.

## Results
The ARIMA(1,1,2) model was selected as the best-fitting model for the Arctic Sea Ice Extent time series data. The model includes AR and MA components, with the MA component being more dominant. The model was validated through Box-Cox transformation and residual analysis.

## How to Use
- **Setup**: Requires R and necessary packages (`forecast`, `tseries`).
- **Usage**: Run `Time Series Analysis - Project 2.Rmd` in RStudio to generate the analysis report. 

## Files
- `README.md`: This file.
- `Time Series Analysis - Project 2.Rmd`: The R script with code and analysis.
- `Time-Series-Analysis---Project-2.html`: The HTML report of the analysis.
- `ArcticSeaIceExtent.csv`: The dataset used for analysis.

## License
This project is licensed under the MIT License.

## Contact
For more information, please contact [Mohammad Rahil](mailto:smrahil98@gmail.com).
