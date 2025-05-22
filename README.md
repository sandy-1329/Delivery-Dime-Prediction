# 🚚 Delivery Time Prediction - Machine Learning Project

This project predicts the delivery duration (in minutes) for an online order based on GPS and order time features. It simulates a real-world scenario for companies like Delivery Hero, Swiggy, or Uber Eats aiming to optimize delivery estimates and logistics operations.

---

## 📌 Project Summary

- **Goal**: Predict how long a delivery will take based on pickup/dropoff location and order time.
- **Model Used**: Random Forest Regressor
- **Final Results**:
  - **MAE**: 1.06 minutes
  - **RMSE**: 1.60 minutes
  - **R² Score**: 0.45
- **Author**: Venkata Sandeep Kumar Reddy

---

## 🧠 Features Used

| Feature         | Description                            |
|----------------|----------------------------------------|
| `order_hour`   | Hour of the day when the order was placed |
| `pickup_lat`   | Latitude of pickup location             |
| `pickup_lng`   | Longitude of pickup location            |
| `dropoff_lat`  | Latitude of dropoff location            |
| `dropoff_lng`  | Longitude of dropoff location           |

---

## 🧼 Data Cleaning Summary

- Removed rows with same pickup/dropoff coordinates
- Dropped rows with missing or null values
- Filtered out unrealistic delivery durations (<5 or >180 minutes)
- Total records after cleaning: **1000 rows**

---

## 📂 Project Structure

```
delivery-time-prediction/
├── delivery_model_training.ipynb        # Final model training notebook
├── cleaned_delivery_data.csv            # Final cleaned dataset (1000 rows)
├── delivery_time_model_simulated.pkl    # Saved Random Forest model
├── Delivery_Time_Prediction_Report.pdf  # Full academic-style report
├── README.md                            # Project documentation
```

---

## ⚙️ How to Use

1. Clone this repo
2. Run `delivery_model_training.ipynb` in Colab or Jupyter
3. Test the trained model with new delivery orders
4. MAE and RMSE will show prediction accuracy

---

## 🌐 Deployment (Optional)

Use Streamlit to deploy a web app that:
- Accepts pickup/dropoff coordinates + time
- Predicts delivery duration using `.pkl` model

---

## 📚 Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Joblib
- Google Colab

---

## 📈 Future Improvements

- Add weather or traffic features
- Deploy with Streamlit or Flask
- Include restaurant and delivery agent behavior

---

## ✅ Status

**Complete** ✅ — Model is trained, tested, and evaluated with strong results.
