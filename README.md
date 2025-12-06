# 📊 Monthly Bill Prediction using Machine Learning

This project predicts a user’s *monthly bill* based on different usage features.  
It demonstrates clean preprocessing, model training, and real-time prediction for new input values.

## 🚀 Project Overview
Monthly bill prediction helps estimate future expenses using historical usage patterns.  
This project includes:

- Data cleaning & preprocessing  
- Handling missing values  
- Feature scaling (StandardScaler / MinMaxScaler)  
- Model training (Random Forest / Linear Regression)  
- Evaluation (MAE, RMSE, R² Score)  
- Predicting monthly bill using user input  

## 🧠 Algorithms Used
- *RandomForestRegressor* (best accuracy for non-linear data)  

 
## 📂 Project Structure
monthly_bill_prediction/  
│── electricity_bill_dataset_800rows.csv  
│── bijali⚡.py
│── README.md  


## 🔧 Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-Learn  
- Matplotlib  

## 📈 Model Performance
- *MAE:* (approx.84)   
- *R² Score:* (approx. 82)

## 🔍 Workflow
1. Load dataset  
2. Clean missing values  
3. Encode categorical columns  
4. Scale numerical columns  
5. Train-test split  
6. Train model  
7. Evaluate metrics  
8. Predict monthly bill for new data
