🚗 Car Price Prediction Model
📌 Overview
This project aims to build and evaluate multiple regression models to predict car prices based on various features. The goal is to understand which model best fits the data and produces the most reliable predictions.

🧪 Models Used
The following regression models were implemented and compared:

Simple Linear Regression

Multiple Linear Regression

Polynomial Regression

📊 Evaluation & Metrics
To evaluate and compare the performance of the models, we used:

R² Score

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

Mean Absolute Error (MAE)

✅ Final Conclusion
After evaluating all three models:

Simple Regression was too basic and failed to capture the complexity of the data.

Polynomial Regression showed signs of overfitting.

Multiple Linear Regression provided the best balance between performance and interpretability.

✅ Final Model Selected: Multiple Linear Regression

🛠 Technologies
Python

Pandas, NumPy

scikit-learn

Matplotlib, Seaborn

📌 Future Improvements
Hyperparameter tuning

Feature engineering (e.g., encoding categorical variables, interaction terms)

Deploy the final model as an API
