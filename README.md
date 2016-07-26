Chulwalar Case Study

Created by: Najeeb, Marvin, Armand Post, Rajeev Kumar

Date: July 25 2016

Purpose:

The purpose of this analysis is to test a variety of forecasting methods for predicting the exports of island of Chuwalhar, part of the island group Urbano.  

Methodology:

The software used to perform the forecasts is RStudio utilizing the “fpp” and “forecast” packages.  These packages allow the use of the below forecasting methods.
•	Simple Exponential Smoothing
•	Holt Linear Trend
•	Holt Exponential Trend
•	Holt Exponential Trend and Dampening
•	Holtz Winter’s with Additive Seasonality
•	Holtz Winter’s with Multiplicative Seasonality


Directory Structure:

A) Data SubFolder:-

Data Folder has raw data.

B) Analysis SubFolder:-

Analysis Folder has RMD file with R code, graphs and mark down files that are used for exploratory purposes.

C) DataDictionary SubFolder:-

DataDictionary Folder has data dictionary of the data.

D) Paper SubFolder:-

This folder has a summary document containing detailed analysis of different models considered for forcasting and recommendation for the best model.


Conclusion:

After performing the analysis, the Holt-Winter’s multiplicative seasonal method was found to be best suited for predicting Chulwalar’s exports.  While the multiplicative seasonal method was more accurate by some measurements (RMSE, MAE, MAPE, and MASE), preference is given to RMSE, MAE, MAPE, and MASE, which the multiplicative seasonal method was found to be more accurate for.  Advice to the Prime Minister of Chulwalar would be to use that method as guidance when planning exports.