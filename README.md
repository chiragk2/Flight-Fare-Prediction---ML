# ✈️ Flight Fare Prediction using Machine Learning

## Project Overview

This project predicts flight ticket prices using Machine Learning techniques.

The objective is to build a regression model that can estimate flight fares based on different features like Airline, Source, Destination, Duration, Stops, and Journey details.

## Business Problem

Flight prices vary depending on multiple factors such as airline, route, duration, and number of stops.

This project helps estimate flight prices using historical flight booking data.

---

## Dataset

Dataset contains flight details including:

- Airline
- Source
- Destination
- Route
- Total Stops
- Journey Date
- Departure Time
- Arrival Time
- Duration
- Price (Target Variable)

---

## Technologies Used

### Programming Language
- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

### Machine Learning Model

- Random Forest Regressor

### Hyperparameter Optimization

- RandomizedSearchCV

---

## Project Workflow

### 1. Data Loading

Loaded training and testing datasets.

### 2. Data Cleaning

- Handled missing values
- Removed unnecessary columns
- Converted date and time features

### 3. Feature Engineering

Created new features:

- Journey Day
- Journey Month
- Departure Hour
- Arrival Hour
- Duration Hours
- Duration Minutes

### 4. Exploratory Data Analysis

Performed analysis on:

- Flight Fare Distribution
- Airline-wise Fare Analysis
- Source and Destination Analysis
- Feature Correlation

### 5. Data Preprocessing

Handled categorical variables using:

- One Hot Encoding
- Label Encoding

### 6. Machine Learning Model

Implemented:

Random Forest Regression

### 7. Hyperparameter Tuning

Used:

RandomizedSearchCV

to improve model performance.

---

## Model Evaluation Metrics

Model performance evaluated using:

- MAE
- MSE
- RMSE
- R2 Score

---

## Results

The Random Forest model successfully predicts flight prices based on historical flight data.

Feature importance analysis identifies major factors affecting flight fares.

---

## Project Files
