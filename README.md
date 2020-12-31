# Fuel Analysis

This repository contains the signal analysis in R for 4 different Fuel related sesnor in order to get the estimated fuel consumption

## Description

In this repository you can find in the DataSet folder the .csv for 4 different Fuel related sensor:

1. Fuel Consumption Sensor
2. Fuel Rate sensor.
3. Fuel Level sensor.
4. Calculated fuel consumption by trip sensor(MSG9).

The main tarjet of this proyect is to smooth the signal from the Fuel Rate sensor and Fuel level sensor in order to get he closses estimated Fuel consumption between
an inicial and a final date, using the data for the Fuel Sensor as a reference to messure the accuracy of the calculated consumption.

## What I learned

- Modeling a fuel Sensor phenomena using time series

- Data Cleaning.

- Procesing of the Data outliers

- Filtering and smoothing related Fuel Sensor Data using the MMF (Moving Mean Filter).

- Filtering and smoothing related Fuel Sensor Data using the Golay filter.

- Calculated fuel cosnsumtion using Riemann-Stieltjes Integral
