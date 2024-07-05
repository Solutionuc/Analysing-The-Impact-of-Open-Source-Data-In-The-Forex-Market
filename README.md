# ANALYSING THE IMPACT OF OPEN-SOURCE DATA ON THE FOREX MARKET: A CASE STUDY OF GBP/USD AND USD/RUB PAIRS

## Overview

This project explores the integration of sentiment analysis and machine learning models to enhance predictive accuracy in Forex trading, focusing on the GBP/USD and USD/RUB currency pairs. The analysis leverages FinBERT for sentiment extraction from newsfeeds and evaluates the performance of Long Short-Term Memory (LSTM) and Random Forest models in forecasting currency price movements.

## Key Components

### Data Collection

- **News Sentiment Data**: Titles, headings, posts, comments, and timestamps.
- **Historical Forex Data**: Date, open, close, high, low, and volume.

### Data Processing

- **Sentiment Analysis**: Utilizes FinBERT to extract sentiment scores from newsfeeds.
- **Data Cleaning**: Removal of duplicates, handling missing values, and normalization.

### Model Training

- **LSTM Model**: 
  - Architecture: Multiple LSTM layers followed by dense layers.
  - Training: Optimized using Adam optimizer and mean squared error loss function.

- **Random Forest Model**: 
  - Configuration: Multiple trees with a focus on minimizing overfitting.
  - Training: Trained on historical Forex data and sentiment scores.

### Evaluation Metrics

- **Performance Metrics**: R², MAE, MSE, and RMSE.
- **Back-Testing**: Evaluates model performance on historical data to assess predictive power.

### Visualization

- **Correlation Heatmaps**: Show relationships between sentiment scores, daily returns, and close prices.
- **Line Charts**: Depict close prices and sentiment scores over time.
- **Model Performance**: Graphs showing predicted vs actual prices and error distributions.

## Results

- **Sentiment Analysis**: Demonstrated some predictive value, especially for GBP/USD.
- **Model Performance**: Random Forest consistently outperformed LSTM in capturing market dynamics and providing reliable predictions.
- **Insights**: Sentiment analysis can enhance trading strategies but requires additional data sources for improved robustness.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Solutionuc/Analysing-The-Impact-of-Open-Source-Data-In-The-Forex-Market.git

