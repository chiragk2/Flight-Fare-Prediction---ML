# ✈️ Flight Fare Prediction using Machine Learning

> An end-to-end Machine Learning project that predicts flight ticket prices using historical flight booking data. The project covers data preprocessing, feature engineering, exploratory data analysis (EDA), model building, hyperparameter tuning, evaluation, and model deployment readiness.

---

## Project Overview

Flight ticket prices vary significantly depending on several factors such as airline, route, departure time, duration, and number of stops. This project builds a Machine Learning regression model capable of predicting flight fares accurately using historical flight data.

The complete workflow includes:

- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Model Building
- Hyperparameter Tuning
- Model Evaluation
- Model Saving

---

## Business Problem

Airline ticket prices change dynamically based on multiple operational factors. Predicting airfare helps travelers make informed decisions and enables travel platforms to provide better pricing insights.

---

## Dataset Information

The dataset contains the following features:

- Airline
- Date of Journey
- Source
- Destination
- Route
- Departure Time
- Arrival Time
- Duration
- Total Stops
- Additional Information
- Price (Target Variable)

---

## Technology Stack

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

### Machine Learning

- Random Forest Regressor

### Hyperparameter Tuning

- RandomizedSearchCV

---

## Project Workflow

### Data Collection

Loaded training and testing datasets from Excel files.

### Data Cleaning

- Missing value handling
- Removed unnecessary columns
- Corrected data types

### Feature Engineering

Created new features including:

- Journey Day
- Journey Month
- Departure Hour
- Departure Minute
- Arrival Hour
- Arrival Minute
- Duration Hours
- Duration Minutes

### Exploratory Data Analysis

Performed detailed analysis to understand:

- Fare Distribution
- Airline-wise Pricing
- Correlation Between Features
- Feature Importance

### Data Preprocessing

- One Hot Encoding
- Label Encoding

### Model Development

Implemented Random Forest Regression for fare prediction.

### Hyperparameter Tuning

Optimized model performance using RandomizedSearchCV.

---

# Exploratory Data Analysis

## Flight Fare Distribution

Understanding the distribution of ticket prices.

![Flight Fare Distribution](Images/fare_distribution.png)

---

## Airline Wise Fare Analysis

Comparison of average fares across different airlines.

![Airline Wise Fare Analysis](Images/airline_price_analysis.png)

---

## Average Airline Fare Comparison

Visualization of average ticket prices offered by different airlines.

![Average Airline Fare Comparison](Images/airline_comparison.png)

---

## Correlation Heatmap

Feature correlation analysis.

![Correlation Heatmap](Images/correlation_heatmap.png)

---

# Model Performance

The model was evaluated using standard regression metrics.

### Evaluation Metrics

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## Actual vs Predicted Flight Fare

Comparison between actual and predicted flight prices.

![Actual vs Predicted](Images/actual_vs_predicted.png)

---

## Feature Importance

Top features contributing to flight fare prediction.

![Feature Importance](Images/feature_importance.png)

---

# Project Structure

```
Flight-Fare-Prediction-ML
│
├── Data
│   ├── Data_Train.xlsx
│   └── Test_set.xlsx
│
├── Images
│   ├── fare_distribution.png
│   ├── airline_price_analysis.png
│   ├── airline_comparison.png
│   ├── correlation_heatmap.png
│   ├── actual_vs_predicted.png
│   └── feature_importance.png
│
├── Flight_Fare_Prediction.ipynb
├── Flight_Fare_Prediction_Model.pkl
├── requirements.txt
└── README.md
```

---

# Project Highlights

- End-to-End Machine Learning Project
- Complete Data Cleaning Pipeline
- Feature Engineering
- Exploratory Data Analysis
- Random Forest Regression
- Hyperparameter Optimization
- Model Evaluation
- Feature Importance Analysis
- Production Ready Project Structure

---

# Future Enhancements

- Streamlit Web Application
- Real-Time Flight Price Prediction
- API Integration
- XGBoost & LightGBM Comparison
- Docker Deployment
- Cloud Deployment (AWS / Azure)

---

# Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Flight-Fare-Prediction-ML.git
```

Go to project folder

```bash
cd Flight-Fare-Prediction-ML
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook
```

---

# Author

## Chirag Kapoor

**Data Analyst | Python | SQL | Power BI | Machine Learning**

---

⭐ If you found this project useful, consider giving it a Star.
