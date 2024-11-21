# Health-Vitals-Monitoring-with-PPG-using-Smartphone-Camera


This repository presents an innovative approach for estimating health vitals such as Heart Rate (HR), Blood Oxygen Saturation (SpO2), Respiratory Rate (RR), and Blood Pressure (BP) using videos captured by smartphone cameras. By leveraging photoplethysmography (PPG) and deep learning techniques, the project demonstrates a non-invasive, cost-effective solution for real-time health monitoring.

Key Features:
PPG Signal Extraction: Using OpenCV to process video frames and extract PPG signals.
Hybrid Model Architecture: A CNN-LSTM-based model processes temporal and spatial data for precise vital estimation.
Real-Time Application: Implemented using TensorFlow Lite for mobile deployment.
Preprocessing and Data Normalization: Adaptive filtering techniques ensure clean and consistent signal inputs.

Dataset:
Fingertip video recordings captured with a Redmi Note 8 smartphone, involving 24 participants aged 5–77.
Ground truth HR values recorded using Andesfit Health pulse oximeter.

Results:
Mean Absolute Error (MAE): 4.07 bpm
Root Mean Squared Error (RMSE): 5.75 bpm
R²: 0.88, reflecting high accuracy and robustness.
Applications:
Sleep and stress monitoring.
Integration into wearable health devices.
Potential for continuous remote health tracking.

For more details on methodology, dataset preprocessing, and results, refer to the project documentation.
