This is a TensorFlow implementation of COVID-19 Forecasting using Temporal Graph Convolutional Network.

## Requirements: (view reqirements.txt for more details)
* tensorflow
* scipy
* numpy
* matplotlib
* pandas
* math

## Run the demo
python3 main.py

Our baselines included: <br>
(1) History Average model (HA)<br>
(2) Autoregressive Integrated Moving Average model (ARIMA)<br>
(3) Support Vector Regression model (SVR)<br>
(4) Graph Convolutional Network model (GCN)<br>
(5) Gated Recurrent Unit model (GRU)<br>

The python implementations of HA/SVR models were in the baselines.py; To run baselines: python3 baselines.py 

## Implement
In this paper, we set time interval as 3 days, 6 days.

In the Italy, France dataset, we set the parameters seq_len 12 and the pre_len to 3, 6 respectively.


