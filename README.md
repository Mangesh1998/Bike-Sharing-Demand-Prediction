# Bike-Sharing-Demand-Prediction

Introduction
Over the last few decades, there has been a significant increase in the popularity of bike-sharing systems all over the world. This is because it is an environmentally sustainable, convenient and economical way of improving urban mobility. 
🎯 The goals of this project are:
 identify key factors affecting the hourly demand for rental bikes.
Build an appropriate regression model to forecast the number of rental bikes required per hour.



📖 Dataset information
Dataset used in this project is the Seoul Bike Share program data.This dataset contains information about the total count of rented bikes at each hour,
as well as the date of observation and meteorological information (Humidity, Snowfall, Rainfall, Temperature Season, and so on) for that hour.
The observations in the dataset were recorded during a span of 365 days, from December 2017 to November 2018.
The Seoul Bike Dataset contains the following information:
Date - The date of each observation in the format 'year-month-day'
Hour - Hour of the day
Temperature - Temperature recorded in the city in Celsius (°C).
Humidity - Relative humidity in %
Wind speed - Speed of the wind in m/s
Visibility - measure of distance at which object or light can be clearly discerned in units of 10m
Dew point temperature - Temperature recorded in the beginning of the day in Celsius(°C).
Solar radiation - Intensity of sunlight in MJ/m^2
Rainfall - Amount of rainfall received in mm
Snowfall - Amount of snowfall received in cm
Seasons - Season of the year (Winter, Spring, Summer, Autumn)
Holiday - Whether the day is a Holiday or not (Holiday/No holiday)
Functional Day -Whether the rental service is available (Yes-Functional hours) or not (No-Non functional hours)
Rented Bike count - Count of bikes rented at each hour (target variable)
🛠️ Tools and Technologies used
The programming language used in this project is Python . The following libraries were used for data analysis and data visualization and to build a classifier to predict the price range of mobile phones.
Pandas : For loading the dataset and performing data wrangling
Matplotlib: For data visualization.
Seaborn: For data visualization.
NumPy: For some math operations in predictions.
    Sklearn: For the purpose of analysis,prediction and evaluation.
📑 Steps involved
Data Preprocessing : Checked for outliers, incorrect values, missing values, duplicates and performed data type correction.
Feature Extraction : Created new columns such as Day, Month, Year, Days_of_week and Weekend from Date column.
Exploratory Data Analysis : Performed Univariate, Bivariate, and Multivariate analysis with various graphs and plots to better understand the distribution of features and their relationships.
Feature Selection : Checked the VIF value (measure of multicollinearity) and dropped Dew point Temperature and Year which were highly correlated with other independent features.
Feature encoding : 
Feature Scaling : Brought features to a similar range using MinmaxScaler.
Implementation of Regression models
Hyperparameter tuning
Comparison of models
💻 Algorithms used
Linear Regression
Polynomial Reg
