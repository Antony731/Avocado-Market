# Project Overview

The objective of this case study is to predict the price of avocado sold in the US using historical dataset.
Data represents weekly 2018 retail scan data for National retail volume (units) and price. 
The data is as follows:

* Date - The date of the observation
* Average Price - the average price of a single avocado
* type - conventional or organic
* year - the year
* Region - the city or region of the observation
* Total Volume - Total number of avocados sold
* 4046 - Total number of avocados with PLU 4046 sold
* 4225 - Total number of avocados with PLU 4225 sold
* 4770 - Total number of avocados with PLU 4770 sold

# Facebook Prophet

Prophet is open source software released by Facebook’s Core Data Science team.
Prophet is a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. 
Prophet works best with time series that have strong seasonal effects and several seasons of historical data. 

Prophet implements an additive regression model with four elements:

* A piecewise linear, Prophet automatically picks up change points in the data and identifies any change in trends.  
* A yearly seasonal component modeled using Fourier series.
* A weekly seasonal component.
* A holiday list that can be manually provided.

Additive Regression model takes the form: 

The functions  are unknown smoothing functions fit from the data 
