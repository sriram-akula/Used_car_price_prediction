🚗 Used Car Price Prediction
📌 Overview

Built a machine learning regression model to predict the current price of used cars based on vehicle specifications and usage data.

📊 Features Used

Car age (years)

Kilometers driven (km)

Engine specs (hp, torque, top speed)

Fuel efficiency (economy)

Condition & rating

On-road price difference (on_road_diff)

Target: current price

🤖 Models Implemented

Multiple Linear Regression

Decision Tree Regressor

Random Forest Regressor (Final Model)

📈 Final Model Performance (Random Forest)

MAE: ~37,729

RMSE: ~45,681

R² Score: 0.85

Random Forest provided the best generalization and lowest prediction error.

🛠 Tech Stack

Python | Pandas | NumPy | Scikit-learn | Joblib

💾 Model Saving
joblib.dump(final_rf, "car_price_rf_model.pkl")
