🚗 Driver Safety: ML-Based Performance Forecasting, Drowsiness Estimation, and Fatigue Diagnosis

📌 Project Overview:
This project focuses on enhancing driver safety by using machine learning models to estimate drowsiness and diagnose fatigue. By predicting a driver's state, we aim to prevent accidents caused by fatigue and drowsiness through real-time monitoring systems in vehicles. This model uses data from multiple physiological signals such as EEG (Electroencephalography), ECG (Electrocardiogram), EMG (Electromyography), as well as sensors, cameras, and user inputs to assess the risk of driver fatigue, offering predictive insights that can trigger timely alerts or interventions.

Why it matters:
Driver fatigue contributes to a significant portion of road accidents. By monitoring drivers' physiological data, we can provide early warnings to help prevent these incidents.



🔧 Installation:
To get started, clone this repository and install the necessary dependencies:

1. Clone the repository:

git clone https://github.com/nixnaxnuxx/drowsy_and_fatigue_detection_for_driving_safety.git
cd driver-safety-ml

2. Install dependencies from the requirements.txt file:

pip install -r requirements.txt

This will install all the libraries required for the project, including TensorFlow, scikit-learn, pandas, matplotlib, and more.



📊 Dataset:
The dataset used in this project consists of driver behavior data collected from various physiological signals, including EEG, ECG, EMG, and vehicle data like speed and acceleration.

Sources:

1. EEG: Brain wave activity used to detect signs of drowsiness or attention levels.
2. ECG: Heart rate and rhythm, which can indicate fatigue or stress.
3. EMG: Muscle tension signals, often used to detect fatigue or physical strain in the driver.

Preprocessing:
1. Data Cleaning: Removed any missing or erroneous data.
2. Normalization: Scaled numerical features (EEG, ECG, EMG signals) to a common range.
3. Feature Extraction: Extracted relevant features like heart rate variability, muscle tension, and brain wave frequency bands.
