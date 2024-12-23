# HDFC-Bank-Stock-Price-Analysis and Forecasting

## Overview
This project focuses on analyzing and predicting the stock prices of HDFC Bank using time series analysis techniques, specifically the SARIMA (Seasonal Autoregressive Integrated Moving Average) and ARIMA (Autoregressive Integrated Moving Average) models. The analysis includes identifying trends, detecting seasonal patterns, and evaluating stock price volatility. The accuracy of the models is assessed using performance metrics such as MAE (Mean Absolute Error), MSE (Mean Squared Error), and RMSE (Root Mean Squared Error). The results offer a comprehensive view of potential future stock price movements, integrating both model-based predictions and the influence of external factors.

## Data Description
The dataset used for this analysis contains historical daily closing prices of HDFC Bank's stock. The data is sourced from a CSV file and includes key information such as the date, closing price, and yearly price changes.

## Exploratory Data Analysis (EDA)

### Yearly Changes
We computed the yearly change in stock prices by subtracting the closing price of the first trading day of the year from that of the last trading day. These yearly changes were visualized using bar charts to highlight the annual gains and losses.

### Stock Prices Over Time
We plotted the historical closing prices of HDFC Bank stock over multiple years to observe the price trends and fluctuations.

### Time Series Decomposition
Seasonal decomposition was performed to uncover underlying seasonal patterns or trends in the stock prices, helping to identify recurring patterns and overall trends.

### Stationarity Testing
To check whether the stock prices were stationary, we applied the Augmented Dickey-Fuller (ADF) test, an essential step in time series analysis.

## Modeling and Forecasting

### SARIMA Model
We divided the data into training and testing sets and then defined and fitted the SARIMA model on the training data. The model was used to forecast future stock prices, and its performance was assessed through evaluation metrics such as MAE, MSE, and RMSE.

### ARIMA Model
Similarly, we defined and fitted the ARIMA model on the training data and used it to predict future stock prices. The performance of the ARIMA model was also evaluated using the same set of metrics.

## Evaluation Metrics
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**

## Results and Insights
Both the SARIMA and ARIMA models demonstrated the ability to predict future stock prices with reasonable accuracy. These models provided valuable insights into potential price trends, though it is important to consider external factors that may affect the stock prices in the future.

## Conclusion
While the analysis and models provide useful guidance on the future trends of HDFC Bank’s stock prices, it is important to approach the forecasts with caution. They should be regarded as potential trends rather than definitive predictions. Continuous monitoring and updating of the models are essential to adapt to changing market conditions.

## Future Work
- Investigate additional external factors that could impact HDFC Bank’s stock prices.
- Implement advanced modeling techniques to improve forecasting accuracy.
- Conduct a thorough risk assessment and develop effective risk management strategies.
