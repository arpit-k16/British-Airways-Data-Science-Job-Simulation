# ✈️ Holiday Booking Prediction

This project uses machine learning to predict whether a customer will complete a holiday booking based on flight behavior, preferences, and trip characteristics.

## 📊 Problem Statement

Customers are more empowered than ever. If an airline waits until the customer reaches the airport to sell them a trip, it’s too late. This project aims to predict booking behavior proactively using historical customer data.

## 📁 Dataset

- 50,000 rows of customer booking and flight preference data
- Target variable: `booking_complete` (1 if customer completed booking)
- Features include:
  - Purchase lead
  - Flight hour & day
  - Route, origin country
  - Extra baggage, in-flight meals, etc.

## 🧠 Machine Learning Approach

- Algorithm Used: Random Forest Classifier (scikit-learn)
- Steps:
  1. Data Cleaning & Encoding (One-Hot Encoding)
  2. Train-Test Split (80/20)
  3. Model Training
  4. Evaluation using accuracy, precision, recall, F1-score
  5. Feature Importance Visualization

## 📌 Top Predictive Features

- Purchase Lead
- Flight Hour
- Length of Stay
- Number of Passengers
- Flight Duration

## 📈 Evaluation

Model evaluated using:
- Confusion Matrix
- Classification Report (Precision, Recall, F1-Score)

## 🖼️ Visualizations

Feature importance chart generated to understand which variables most influence booking completion.



## 💡 Insights

- Early planners and long-stay travelers are more likely to complete bookings
- Day and time of flight matter
- Booking origin and customer preferences (like baggage and meals) play a role

## 📦 Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- PowerPoint for Summary Slide

## 📂 Files

- customer_booking.csv — Input dataset
- BA-TASK2.ipynb — Cleaned Jupyter notebook
- insights.pptx — PowerPoint summary
- README.md — Project documentation



---

