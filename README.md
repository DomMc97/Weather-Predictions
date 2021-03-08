# Prediction of the minimum daily temperatures in the city Melbourne, Australia

## Overview

A project in which I predict the minimum daily temperatures in the city Melbourne, Australia. Using a univariate dataset of the minimum daily temperatures over 10 years (1981-1990) in Melbourne from the Australian Bureau of Meteorology.

## ARIMA Model

The first set of predictions are made using the ARIMA model and its adapted version to account for seasonality. As expected the seasonal adapations have the best performance for weather variables. 

## LSTM Models

The second set of predictions are made using neural networks containing LSTM blocks. This includes daily predictions with a window of 6 and 365 which although the predictions are marginally better for 365 the increase in performance is outweighed by increased computational costs. The final predictions are for the weekly and annual weather predictions.
