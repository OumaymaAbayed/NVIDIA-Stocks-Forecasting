# NVIDIA-Stocks-Forecasting

# NVIDIA Stock Prediction using ARIMA and Fourier Transform 📈🔮

This project uses **Exploratory Data Analysis (EDA)** and the **ARIMA (AutoRegressive Integrated Moving Average)** model to predict the future stock prices of **NVIDIA** based on historical data. The project also utilizes **Fourier Transform** to uncover seasonality and periodic components in the stock prices, which further aid in building a more accurate predictive model.

## Data Source:
kaggle link: https://www.kaggle.com/datasets/muhammaddawood42/nvidia-stock-data

## Project Structure 🗂️
📦 NVIDIA-Stocks-Forecasting
├── 📄 README.md  
├── 📂 data  
│   ├── NVIDIA_STOCK.csv  
├── 📂 script  
│   ├── Time_Series_Forecasting.ipynb  
└── 📂 graphs  

## Key Insights and Conclusions 🧠💡

### Seasonality and Trends 📊:
- **Fourier Transform Analysis** reveals significant periodic components in NVIDIA's stock prices, suggesting the presence of seasonality. These cycles offer crucial insights into the recurring patterns and help refine the predictive model.
- **Seasonal Decomposition of Time Series** highlights clear trends and seasonal patterns, allowing a better understanding of the underlying structure in stock price movements.

### Autocorrelation and Partial Autocorrelation 🔄:
- **Autocorrelation and Partial Autocorrelation Plots** provide evidence that past prices influence future prices to a significant extent. The presence of significant lags points to the potential effectiveness of time-series models like ARIMA for predicting stock price behavior.

### ARIMA Modeling 📉:
- The **ARIMA model** is applied to the stock data, and the predictions align reasonably well with the actual stock prices. This model captures key dependencies in the data, making it useful for forecasting future stock prices.
- However, the ARIMA model might not be the most accurate in every scenario, and further tuning or more complex models might be required for better performance.

### Conclusion 🔍:
This analysis of NVIDIA’s stock data offers valuable insights into the company’s market behavior over time. Some key takeaways include:
- The identification of trends and seasonality patterns in the stock prices.
- The significant role of autocorrelation in forecasting stock prices.
- The usefulness of the ARIMA model in predicting future stock prices, with potential for improvements.

For investors and market analysts, understanding these patterns is critical for making informed decisions. It's important to consider external factors, such as company news or broader market conditions, that may impact stock performance. This project demonstrates how analytical techniques like Fourier Transform, EDA, and ARIMA can be employed to explore and predict stock price movements.



