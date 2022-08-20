# Airlines_tickets_sales_prediction
The objective of this project is to implement and explore different Time series Forecasting techniques like ARIMA, SARIMA, PROPHET and XGBOOST on a relatively simple and clean dataset.

A Time Series is defined as a series of data points recorded at different time intervals. The time order can be daily, monthly, or even yearly.

Time Series forecasting is the process of using a statistical model to predict future values of a time series based on past results.


# Dataset
The dataset used in this project is International airline passengers dataset. It contains monthly total number of passengers (in thousands) and has two columns – month and count of passengers.

# Results

## 1. ARIMA model-
<img width="1009" alt="Screenshot 2022-08-13 at 3 54 48 PM" src="https://user-images.githubusercontent.com/97120462/184479635-eb1c2ca6-2c9d-4a45-8466-fc11e724ff29.png">

**MAPE Value- 23.16%**


<img width="251" alt="Screenshot 2022-08-15 at 8 27 30 PM" src="https://user-images.githubusercontent.com/97120462/184659703-0740d6ef-7dab-4c78-a224-dc666bc0b32e.png">


## 2. SARIMA model-
<img width="1009" alt="Screenshot 2022-08-13 at 3 56 26 PM" src="https://user-images.githubusercontent.com/97120462/184479681-de083131-a37b-4a49-b032-9f1cd370e181.png">

**MAPE Value- 19.23%**

<img width="252" alt="Screenshot 2022-08-19 at 12 04 26 PM" src="https://user-images.githubusercontent.com/97120462/185557851-036e0456-d41e-498a-968a-f06a7f50d78b.png">



## 3. Prophet model-

<img width="1089" alt="Screenshot 2022-08-13 at 4 04 41 PM" src="https://user-images.githubusercontent.com/97120462/184479935-b933121c-2d30-4c79-a455-c7a64a9d2157.png">

**MAPE Value = 14.27%**

<img width="463" alt="Screenshot 2022-08-19 at 12 30 55 PM" src="https://user-images.githubusercontent.com/97120462/185562233-a91a609c-41ad-4030-b75e-3bf1de5108fb.png">


## 4. XGBoost model-
<img width="1097" alt="Screenshot 2022-08-13 at 4 08 50 PM" src="https://user-images.githubusercontent.com/97120462/184480059-82e3ba3b-e534-490d-a168-974d351d5fc6.png">

**RMSE value for XGBOOST model is=  69.16**

<img width="926" alt="Screenshot 2022-08-19 at 12 32 48 PM" src="https://user-images.githubusercontent.com/97120462/185562553-968bd1bf-1a9a-408e-8ea5-b1228f05e54a.png">

### Conclusion-

1. Analyzed the given data to check for stationarity & decomposed it to get level, trend, seasonality, and residue
2. Performed ADF test for stationarity & used ARIMA, SARIMA, Prophet and XGBoosT to predict future sales
3. Achieved best accuracy of 19.23% MAPE in SARIMA & 14.27% MAPE by implementing the Prophet model

**Submitted by-**  
1. **Vaibhav Singh Panwar**  https://github.com/PanwaR1010
2. **Vivek Kumar**  https://github.com/vivekkumar-creator
