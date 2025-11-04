# Study-Hotel Booking Demand_Cancellation prediction
Predicting hotel booking cancellations using machine learning on the Hotel Booking Demand dataset
# Hotel Booking Demand – Cancellation Prediction

This project predicts whether a hotel booking will be **canceled or not** using the [Hotel Booking Demand dataset](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand).

## 📂 Files

- `Hotel_booking_demand.ipynb` – main Google Colab notebook  
- `feature_importance.png` – top predictive features  
- `confusion_matrix.png` – model performance visualization  

## 🎯 Project Goal

- Understand which factors (lead time, ADR, deposit type, special requests, etc.) influence cancellations.
- Build machine learning models (Random Forest, Gradient Boosting, etc.) to predict cancellations.
- Provide business insights for hotel revenue management and overbooking strategy.

## 🧠 Main Techniques

- Feature engineering:
  - `total_stay`, `total_guests`, `price_per_person`
  - `early_booking`, `long_stay`, `high_adr`
- Models:
  - Random Forest
  - Gradient Boosting
- Evaluation:
  - Accuracy, precision, recall, F1-score
  - Confusion matrix
  - Feature importance

Download the dataset from Kaggle:  
 [Hotel Booking Demand Dataset]

## 📊 Business Insight (Short)

The model shows that:
- **ADR (price)** and **lead time** are major drivers of cancellations.
- **Non-refundable deposits** dramatically reduce cancellations.
- Guests with **more special requests** and **parking spaces** are less likely to cancel.

This project is part of my MS in Business Analytics journey and my research interest in **hotel revenue management and AI-driven optimization**.
