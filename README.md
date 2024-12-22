# ISS_ML_Project
Satellite Position Prediction Using Machine Learning and Kalman Filter
Overview
This project aims to predict the position of satellites in orbit using two approaches:

A Machine Learning (ML) model for learning the satellite trajectory from data.
A Kalman Filter with a Constant Velocity (CV) model for mathematical prediction.
The results are compared to evaluate the accuracy of both approaches.

Purpose
Satellite position prediction is essential for:

Navigation and communication systems.
Preventing collisions between satellites.
Efficient satellite tracking and ground station operations.
What It Does
Machine Learning Model: Trains on historical satellite position data to predict future positions.
Kalman Filter: Uses the CV model to estimate future positions based on physical equations of motion.
Comparison: The RMSE (Root Mean Square Error) of predictions from both methods is calculated to determine which approach is more accurate.
Key Results
RMSE Comparison:
ML Model RMSE: 500.0
Kalman Filter CV Model RMSE: 119.52
The Kalman Filter outperformed the ML model in terms of accuracy.
How It Works
Input satellite position data is preprocessed.
The ML model is trained and saved.
Kalman Filter predictions are generated.
Results are plotted and evaluated using RMSE.
Conclusion
While Machine Learning has potential for complex systems, in this case, the Kalman Filter provides a more precise prediction for satellite positions, thanks to its reliance on physical models.
