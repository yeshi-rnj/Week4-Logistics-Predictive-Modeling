
# Week 4 - Predictive Modeling and Optimization in Logistics Systems

## Project Overview

This project applies predictive modeling and optimization techniques to a logistics delivery-time forecasting problem.

The objective is to predict delivery time based on operational, route, weather, warehouse, vehicle, and order-related factors.

## Dataset

A synthetic dataset containing 10,000 shipment records was generated using Python.

### Features

- shipment_volume
- distance_km
- weather_delay_min
- traffic_level
- warehouse_load_pct
- driver_experience_years
- vehicle_age_years
- order_priority
- stops_count

### Target

- delivery_time_min

## Machine Learning Models

Three regression models were evaluated:

1. Linear Regression
2. Random Forest Regression
3. Gradient Boosting Regression

## Evaluation Metrics

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R-squared (R2)

Five-fold cross-validation was also performed.

## Optimization Strategies

- Dynamic route planning
- Warehouse workload balancing
- Driver assignment
- Stop consolidation
- Vehicle maintenance
- Traffic-aware scheduling
- Weather-aware planning
- Priority-aware dispatch

## Technologies

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab
- GitHub

## Project Workflow

Data Simulation
-> Data Exploration
-> Preprocessing
-> Train/Test Split
-> Model Training
-> Model Evaluation
-> Cross Validation
-> Feature Importance
-> Hyperparameter Tuning
-> Optimization Scenario
-> Recommendations

## Conclusion

The project demonstrates how predictive analytics can help logistics organizations forecast delivery times and make data-driven operational decisions.
