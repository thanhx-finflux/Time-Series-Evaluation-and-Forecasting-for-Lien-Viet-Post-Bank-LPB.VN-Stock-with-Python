# Time-Series-Evaluation-and-Forecasting-for-Lien-Viet-Post-Bank-LPB.VN-Stock-with-Python

### Overview
This project analyzes and forecasts stock prices for Lien Viet Post Bank (formerly Fortune Vietnam Joint Stock Commercial Bank) using historical data from yfinance (from January 2, 2020, to recent data). 

It includes data evaluation, volatility calculation, and forecasting with methods like moving averages, exponential smoothing, and Holt-Winters.

As of September 26, 2025, LPB.VN 48,500 VND suggests holding long positions.
### Key Features

- Data fetching with yfinance
- Log returns and annualized volatility calculation.
- Forecasting: Moving average, Exponential smoothing (simple, Holt's, Holt-Winters)
- Evaluation metric: MSE, MAE, RMSE.

# Visualizations
- Plotting Resampled Lien Viet Post Bank (LPB) Closing Prices from 2020-01-31 to 2025-09-30

<img width="1033" height="545" alt="Image" src="https://github.com/user-attachments/assets/20b9c047-8b73-4b95-9b58-2e150adbe47f" />

- Histogram of Daily Log Returns for LPB

 <img width="997" height="545" alt="Image" src="https://github.com/user-attachments/assets/c65096eb-c540-4bcf-ad63-8d28f499ef26" /> 

 - Plot moving average vs actual prices from 120 days ago to today

<img width="1021" height="545" alt="Image" src="https://github.com/user-attachments/assets/dcb1c782-12f4-4440-a48a-a0c741ad0b77" />

- Plotting Weekly Resampled Lien Viet Post Bank (LPB) Closing Prices from 2020-01-03 to 2025-09-26

<img width="1011" height="545" alt="Image" src="https://github.com/user-attachments/assets/d10a9bae-f969-4fc8-a0b8-25c88a54bbb2" />

### Results
- Holt-Winters Exponential Smoothing (Additive), which can model both trend and seasonality in the data.

      2025-10-03    48.507782
      2025-10-10    48.965564
      2025-10-17    49.423346
      2025-10-24    49.881128
      2025-10-31    50.338909
      2025-11-07    50.796691
      2025-11-14    51.254473
      2025-11-21    51.712255
      2025-11-28    52.170037
      2025-12-05    52.627819
      2025-12-12    53.085601
      2025-12-19    53.543383
      Freq: W-FRI, dtype: float64

- Holt's Damped Trend Method, which is a variation of Holt's linear method that includes a damping parameter to reduce the trend over time.

      2025-10-03    48.510483
      2025-10-10    48.968664
      2025-10-17    49.424553
      2025-10-24    49.878163
      2025-10-31    50.329506
      2025-11-07    50.778591
      2025-11-14    51.225431
      2025-11-21    51.670037
      2025-11-28    52.112420
      2025-12-05    52.552591
      2025-12-12    52.990561
      2025-12-19    53.426341
      Freq: W-FRI, dtype: float64

  ### Technology
      numpy
      pandas
      yfinance
      matplotlib
      seaborn
      scipy
      statsmodels

### Contact
- Thanh Xuyen Nguyen
- LinkedIn: xuyen-thanh-nguyen-0518
- Email: thanhxuyen.nguyen@outlook.com
