# Volatility Forecasting using Temporal Convolutional Networks and ARCH family models

*Divya Patel, Joaquin Garay, and Roger Li*

NYU Tandon MS Financial Engineering Students
Fall 2024


## Abstract

This project explores the use of Temporal Convolutional Networks (TCNs) for forecasting equity market volatility, a key metric in risk management and asset allocation. While traditional models such as Generalized Autoregressive Conditional Heteroskedasticity (GARCH) and its variants have been widely utilized, TCNs offer distinct advantages, including enhanced parallel processing and the ability to capture short-term dependencies. This research uses return data and intraday volatility measures to compare the predictive performance of a log-linear Realized GARCH(1,2) model and a TCN. The results show that TCNs outperform the Realized GARCH model across 39 out of 40 sample cases based on metrics like Mean Squared Error (MSE) and Root Mean Squared Error (RMSE). Still, there’s no clear outperformance on Mean Square Error (MAE), suggesting that Realized GARCH may perform better on low volatility regimes than TCN. Furthermore, computational performance analysis indicates that TCNs are competitive with GARCH models, demonstrating their feasibility for real-time implementation in financial risk management.
