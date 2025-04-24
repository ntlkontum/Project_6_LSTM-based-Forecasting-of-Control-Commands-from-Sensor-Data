# Project 6: LSTM based Forecasting of Control Commands from Sensor Data

## Objective
To build a machine machine learning/deep learning model (LSTM) capable of accurately predicting two binary (on/off - 0/1) control commands of a system, based on time-series measurement data of six input variables. This aims to automate system control (autonomous control) and enable a faster response to changes in the system environment.

## Requirement
Read in .txt file (requirements.txt)

## Input and Output
- Input:   6 time-series variables, describing system performance metrics
- Output:  2 binary (0/1) variables representing system control commands (On/Off

## Dataset: 
Two .csv files include: traning and testing (No NaN values)
- Training: 8 Variables (6 features, 2 targets), Time-series data, Records: 259,200, Sampling frequency: 1 Hz
- Testing: 8 Variables (6 features, 2 targets), Time-series data, Records: 51,840 (20% Training), Sampling frequency: 1 Hz

## Project Outcomes
- Conducted exploratory data analysis (EDA) on time-series data to identify outliers, understand trends and seasonality, and assess stationarity for model selection.
- Completed building an LSTM model with high accuracy (96.8%)
- Evaluated using other metrics such as Precision, Recall, and F1-Score

