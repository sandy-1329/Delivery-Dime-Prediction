# 🚚 Delivery Dime Prediction – ML ETA Estimator


This project predicts delivery time (in minutes) for food delivery orders using real-world-inspired features like distance, order size, and traffic delays. Built as a simulation of Delivery Hero’s backend ML system.

## 📊 Problem Statement
Restaurants and delivery platforms struggle with ETA accuracy. This model helps predict delivery time more accurately to improve customer satisfaction and operational planning.

## 📁 Dataset
A realistic synthetic dataset was created with features:
- `order_time`, `pickup_time`, `delivery_time`
- `distance_km`, `num_items`, `delivery_zone`, `weather`, etc.

## 🧹 Data Cleaning
- Removed missing/duplicate values
- Corrected unrealistic delivery durations
- Fixed GPS/location errors

## 🏗️ Feature Engineering
- Calculated `estimated_duration`, `delay`, `prep_time`
- Extracted time-based features (hour, weekday)
- Normalized distances and encoded categories

## 🤖 Models Used
- Linear Regression
- Random Forest Regressor (**Best**)

## ✅ Results
- MAE: **1.06 mins**
- RMSE: **1.60 mins**
- R²: 0.45

## 📈 Visualizations
- Feature importance
- Error distributions
- Predicted vs Actual

## 🛠️ Tech Stack
- Python, Pandas, Scikit-learn, Matplotlib, Seaborn
- Google Colab

## 🚀 How to Use
1. Clone the repo
2. Open the notebook in Colab
3. Run cells step-by-step
4. Try your own input data for predictions!

## 📄 Report
View the full academic PDF report [here](https://github.com/sandy-1329/Delivery-Dime-Prediction/blob/main/Delivery_Dime_Report.pdf)


## 🧠 Author
Venkata Sandeep Kumar Reddy  
Contact: [LinkedIn](https://www.linkedin.com/in/venkatasandeepr/) | <!-- Portfolio link can be added later -->


