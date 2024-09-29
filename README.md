# Forecasting Energy Prices Using Machine Learning Methods

## Overview

This repository contains the code and resources used for my master's thesis titled "Forecasting Energy Prices Using Machine Learning Methods." The goal of this thesis is to forecast natural gas prices at the TTF hub in the Netherlands using a variety of machine learning models. The project utilizes monthly data from March 2010 to April 2024, covering both market and economic data as independent variables.

## Objectives

1. Model Comparison: Compare several machine learning methods to determine the most effective approach for forecasting natural gas prices. The models used include:

- Random Walk (for benchmarking purposes)
- Autoregression (AR)
- Lasso, Adaptive Lasso
- Ridge Regression
- Elastic Net
- Random Forest, Bagging
- Support Vector Regression (SVR)
- Long Short-Term Memory (LSTM)

2. Data Segmentation: Analyze how different data windows (rolling and expanding) influence the performance of these models.

3. Economic Data Impact: Investigate how the inclusion of economic indicators (such as GDP, inflation, and interest rates) affects the accuracy of the forecasting models.

4. Energy Price Forecasting: Provide insights into the challenges and limitations of forecasting energy prices in Europe, especially considering the availability of limited data compared to the U.S.

## Methodology

This project employs several machine learning models and econometric techniques to forecast energy prices, including:

- Benchmark Model: A simple Random Walk model is used as a baseline for comparison.
- Autoregressive Models: Traditional statistical methods used to model the dependence of a variable on its own past values.
- Penalized Regression Models: Lasso, Ridge, Adaptive Lasso, and Elastic Net are implemented to handle potential overfitting and to select the most important variables.
- Ensemble Learning: Random Forest and Bagging methods are used to reduce variance and improve the robustness of predictions.
- Support Vector Regression (SVR): A powerful machine learning algorithm effective for small to medium-sized datasets.
- LSTM Neural Networks: Used to capture long-term dependencies in sequential data, such as time series.
