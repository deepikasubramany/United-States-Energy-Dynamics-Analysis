# United-States-Energy-Dynamics-Analysis

Energy is a cornerstone of the United States' economic infrastructure, playing a pivotal role in sustaining the nation's growth and development. The production and consumption of energy form the backbone of various sectors, influencing not only economic prosperity but also the day-to-day activities of the American populace. As a crucial player in the global energy arena, the United States grapples with the dual challenge of meeting increasing energy demands while navigating the imperative for sustainable practices.

## Problem Statement:

This project aims to conduct a comprehensive analysis of the historical trends in energy consumption and production in the United States, spanning a period of 27 years. Additionally, it seeks to examine the evolving dynamics of economic variables such as Stock Change and Consumer Price Index. The project involves the impact of these variables on both production and consumption for the six-year period (2022-2016) using various models that will be fitted for the rest of the years. The ultimate goal is to assess the accuracy of the forecasts by comparing them with the actual values available in the dataset.

## The Data

The foundation of our analysis lies in data sourced from the U.S. Energy Information Administration, which can be accessed at U.S. EIA Open Data (https://www.eia.gov/opendata/). The dataset contains 2194 entries and 9 columns. After filtering and addressing missing values, the dataset now consists of 336 rows and 6 columns. Dependent variables include Energy Consumption and Production, while independent variables include Stock Change and Consumer Price Index.

In the model selection process, various forecasting techniques were explored, including Holt’s Winters Exponential Smoothing, Simple Regression, Classical Decomposition, Multiple Regression Analysis, Multiple Regression with Seasonality, and ARIMA Model. Among these, the Classical Decomposition model emerged as the most robust and accurate forecasting approach, showcasing low prediction errors and high accuracy. This model's ability to decompose time series data into distinct components proved superior, making it a compelling choice for forecasting Total Production and Total Consumption in the dataset.
