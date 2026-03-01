# Data-Cleaning-Pre-processing

# About This Project
This project is about cleaning and preparing flight price data for machine learning models.
I worked on raw flight data and transformed it into a structured format so it can be used for training models like regression algorithms.

Final dataset shape: (10682, 42)
That means 10,682 rows and 42 cleaned features ready for modeling.

# Project Goal
The main goal of this project is:
Clean raw flight data
Convert date & time columns into useful numerical features
Handle categorical variables
Create new useful features
Prepare the dataset for machine learning models
Basically, this is data preprocessing + feature engineering.

# What I Did (Data Cleaning Steps)
1. Date & Time Processing
Extracted:
Date
Month
Year
Arrival Hour & Minutes
Departure Hour & Minutes
Converted duration into:
Duration Hour
Duration Minute
Total Duration (in minutes)
Handling Categorical Columns

2. Applied one-hot encoding to:
Airline
Source
Destination
Additional Info
Example:
Airline_Air India
Airline_IndiGo
Source_Delhi
Destination_Cochin

3. Feature Engineering
Created new meaningful features like:
Total_Duration(min)
Duration(min)
Time-based features
Layover related features

4. Data Type Conversion
Converted all usable columns into numeric format
Final dataset contains mostly int64 and float64 types
Only required categorical column kept as object

# Final Dataset Info
Rows: 10,682
Columns: 42
Target Variable: Price
All features are machine learning ready

# This cleaned dataset can now be used for:
Linear Regression
Random Forest
XGBoost
Gradient Boosting
Or any regression model

# What I Learned
Real-world data is messy
Feature engineering is very important
Date & time columns can give powerful insights
Proper encoding is required before training ML models

# Conclusion
This project helped me understand how raw data becomes model-ready data.
Data cleaning and feature engineering are very important steps in data science.
