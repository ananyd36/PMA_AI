# Global Weather Data Analysis and Forecasting

This repository contains an analysis and modeling of global weather data, with a focus on forecasting temperature, precipitation, and humidity using ARIMA and LSTM models.

## Dataset Overview
The dataset used comprises 59,633 rows and 41 columns, containing weather information from various countries and locations worldwide. It is free of missing values and duplicate rows, ensuring data quality.

### Key Highlights:
- **Country with minimum occurrences**: Afghanistan
- **Country with maximum occurrences**: Zimbabwe
- **Highest recorded temperature**: 49.2°C (Kuwait)
- **Lowest recorded temperature**: -24.9°C (Ulaanbaatar, Mongolia)
  
## Temperature Analysis
### Key Findings:
- **Highest recorded temperature**: 49.2°C (Kuwait)
- **Lowest recorded temperature**: -24.9°C (Mongolia)

## Location Analysis
- **Highest latitude**: Reykjavik, Iceland
- **Highest longitude**: Funafuti, Tuvalu
- **Most frequent countries**: Bulgaria, Indonesia, Turkey

## Date and Time Observations
- **Dataset update duration**: From May 16, 2024, to March 20, 2025
- **Updates in 2024**: 44,469
- **Updates in 2025**: 15,359

## Modeling Experiments
### 1. ARIMA Modeling
**Objective**: Forecast temperature, precipitation, and humidity using ARIMA.
- **Modeling process**: Data preprocessing, model training, and performance evaluation using RMSE, MAE, and MAPE.
- **Results**: Models showed reasonable performance but require fine-tuning for better accuracy.

### 2. LSTM Modeling
**Objective**: Forecast temperature using Long Short-Term Memory (LSTM) networks.
- **Modeling process**: Data scaling, sequence creation, model training, and evaluation using RMSE.
- **Results**: The LSTM model showed good performance in training but exhibited overfitting during testing.

## Conclusion
Both ARIMA and LSTM models provided valuable insights into weather forecasting. While the ARIMA models showed limited performance, the LSTM model demonstrated potential in capturing complex temporal patterns in temperature data. Further feature engineering and model fine-tuning are needed to improve accuracy.

## Future Work
I will continue to refine the models, including addressing data preprocessing and feature engineering to enhance forecasting accuracy.

## Check out my work
- [GitHub](https://github.com/ananyd36)
- [LinkedIn](https://www.linkedin.com/in/ananyd36/)

