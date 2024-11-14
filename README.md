# Nasdaq Closing Price Prediction Challenge

## Description
This project focuses on developing a predictive model to forecast closing price movements for Nasdaq-listed stocks during the crucial final 10 minutes of each trading day. By leveraging data from the order book and the closing auction, the goal is to gain insights into supply and demand dynamics, as well as identify potential trading opportunities.

## Objective
To build a robust model that can:
- Predict closing price movements for a diverse range of Nasdaq-listed stocks.
- Use key information from the order book and the closing auction to enhance prediction accuracy.

## Dataset
The dataset includes:
- **Order Book Data**: Captures real-time market activity such as bid and ask prices, order volume, and market depth.
- **Closing Auction Data**: Provides information related to the closing auction mechanics.
- **Closing Price Movements**: Historical data of stock price movements during the final minutes of trading.

## Evaluation Criteria
The performance of the predictive model is evaluated using the **Mean Absolute Error (MAE)** formula:

$$
MAE = \frac{1}{n} \sum_{i=1}^n |y_i - \hat{y}_i|
$$

Where:
- $n$: Number of data points.
- $y_i$: Actual observed value.
- $\hat{y}_i$: Predicted value.

Lower MAE values indicate better model performance.

## Challenges and Considerations
- **Combining Order Book and Auction Data**: Effectively merge these data sources to extract meaningful insights and create accurate predictions.
- **Supply and Demand Dynamics**: Accurately model supply and demand interactions to understand price movement trends.
- **Trading Opportunities**: Identify and capture trading opportunities in the final moments of the trading session.
