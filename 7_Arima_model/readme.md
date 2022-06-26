### ARIMA Model (Auto-Regressive Integrated Moving Average)

#### ● Exponential smoothing models were based on a description of level, trend and seasonality in the data
#### ● ARIMA models aim to describe the correlations in the data with each other

### Parameters of ARIMA model

#### ● ARIMA has three parameters

 ○ AR - Lags describing autocorrelation: (p)
 ○ I - Number of differencing for stationarity (q)
 ○ MA - Lags describing partial autocorrelation (d) 

### Steps to Build ARIMA Model
#### 1. Check if the series is stationary
#### 2. Find the value of d required to make series stationary
#### 3. Find the value of p and q using the ACF and PACF plots
#### 4. Build ARIMA model
#### 5. Make prediction
