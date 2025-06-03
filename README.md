# 🚗 Used Car Price Estimator

## 📋 Overview
The **Used Car Price Estimator** is a machine learning project designed to predict the market price of used cars based on features such as mileage, car age, make, model, fuel type, transmission, and year of manufacture. This tool helps buyers and sellers to estimate fair prices for vehicles using historical data and predictive modeling.

## ⚙️ Features
- 🧹 Data preprocessing and outlier removal  
- 🔧 Feature engineering (calculating car age from the manufacturing year)  
- 🏷️ Encoding categorical variables (make, model, fuel, transmission)  
- 🌲 Predictive modeling using Random Forest Regression  
- 📊 Evaluation with Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE)  
- 🚀 Sample prediction interface for quick price estimation

## 📊 Dataset
The dataset includes the following features:
- 🛣️ `mileage` (numeric): Distance the car has traveled (in kilometers)  
- ⏳ `car_age` (numeric): Calculated as current year (2025) minus manufacturing year  
- 🏭 `make` (categorical): Manufacturer of the car (e.g., Toyota, Honda)  
- 🚘 `model` (categorical): Car model (e.g., Corolla, Civic)  
- ⛽ `fuel` (categorical): Fuel type (e.g., gas, diesel)  
- ⚙️ `transmission` (categorical): Transmission type (automatic/manual)  
- 📅 `year` (numeric): Year of manufacture  
- 💰 `price` (numeric): Market price of the car (in local currency)

## 🚀 Getting Started

### 🛠️ Prerequisites
- Python 3.x  
- pandas  
- scikit-learn  
- numpy  

You can install dependencies with:  

pip install pandas scikit-learn numpy

💻 Usage
Load the dataset cars_dataset.csv.

Run the training script to build the model.

Use the model to predict used car prices based on input features.

# Train and predict steps here...
📈 Evaluation Metrics
🎯 Mean Absolute Error (MAE): Measures average magnitude of errors

📉 Root Mean Squared Error (RMSE): Penalizes larger errors more heavily

📜 License
This project is licensed under the MIT License.

