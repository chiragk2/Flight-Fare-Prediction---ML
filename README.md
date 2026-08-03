# ✈️ Flight Fare Prediction using Machine Learning

## Project Overview

This project focuses on predicting flight ticket prices using Machine Learning techniques.

The objective is to build a regression model that can estimate flight fares based on various factors such as Airline, Source, Destination, Duration, Journey details, and Number of Stops.

---

# Business Problem

Flight ticket prices depend on multiple factors and change frequently.

This project helps in understanding the key factors affecting flight prices and predicts the expected fare using historical flight data.

---

# Dataset

The dataset contains flight booking information with features:

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

# Technologies Used

## Programming Language

- Python

## Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Machine Learning Algorithm

- Random Forest Regressor

## Hyperparameter Optimization

- RandomizedSearchCV

---

# Project Workflow

## 1. Data Loading

Loaded training and testing datasets and performed initial data inspection.

## 2. Data Cleaning

Performed:

- Missing value handling
- Data type conversion
- Removal of unnecessary columns

## 3. Feature Engineering

Created new features from existing data:

- Journey Day
- Journey Month
- Departure Hour
- Departure Minutes
- Arrival Hour
- Arrival Minutes
- Duration Hours
- Duration Minutes

## 4. Exploratory Data Analysis (EDA)

Performed analysis to understand:

- Flight fare distribution
- Airline-wise pricing
- Feature relationships
- Important factors affecting flight prices

## 5. Data Preprocessing

Handled categorical variables using:

- One Hot Encoding
- Label Encoding

## 6. Model Building

Implemented:

**Random Forest Regression**

to predict flight ticket prices.

## 7. Hyperparameter Tuning

Used:

**RandomizedSearchCV**

to improve model performance and select the best parameters.

---

# Exploratory Data Analysis (EDA)

## Flight Fare Distribution

Analyzed the distribution of flight ticket prices.

![Flight Fare Distribution](Images/fare_distribution.png)


---

## Airline Wise Fare Analysis

Compared average flight prices across different airlines.

![Airline Analysis](Images/airline_price_analysis.png)


---

## Feature Correlation Heatmap

Performed correlation analysis to identify relationships between features.

![Correlation Heatmap](Images/correlation_heatmap.png)


---

# Model Performance

The Random Forest Regression model was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R2 Score


## Actual vs Predicted Flight Fare

Comparison between actual flight prices and predicted prices.

![Actual vs Predicted](Images/actual_vs_predicted.png)


---

# Feature Importance

Identified the most important features influencing flight fare prediction using Random Forest feature importance.

![Feature Importance](Images/feature_importance.png)


---

# Project Structure
