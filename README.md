🚗 Car Purchase Amount Predictor
A high-accuracy deep learning model to predict car purchase amounts based on customer profiles.

🎯 Project Goal

This project delivers a powerful deep learning model that accurately predicts how much a customer will spend on a car, using their demographic and financial data. Perfect for automotive sales, financing, and market research!

📊 About the Data

We used a real-world Car Purchasing Dataset containing:
✔ Customer profiles: Name, Email, Country, Gender, Age
✔ Financial data: Annual Salary, Credit Card Debt, Net Worth
✔ Target value: Car Purchase Amount (in USD)

The data was split into train/test sets for robust model validation.

🤖 Model & Techniques

🔹 Deep Learning Approach:

Built a neural network using TensorFlow/Keras for high-precision predictions.
Optimized hyperparameters with GridSearchCV (scikit-learn) to boost performance.
🔹 Key Features:
✅ Handles numerical and categorical data
✅ Scalable for large datasets
✅ Tunable for business-specific accuracy needs

📈 Performance & Results

We rigorously evaluated the model using:

R² Score (R-squared): Measures how well the model explains variance (closer to 1 = better).
RMSE (Root Mean Squared Error): Tracks prediction errors in USD (lower = more accurate).
MSE (Mean Squared Error): Ensures robust error analysis.
*(Example: Our best model achieved R² = 0.95, meaning it explains 95% of purchase amount variability!)*
