# Project Overview 
This project leverages photoplethysmography (PPG) signals and machine learning techniques to predict systolic, diastolic, and arterial blood pressure (SBP, DBP, ABP) non-invasively. It aims to contribute to continuous cardiovascular health monitoring.

# Features
 - Denoising of PPG signals using wavelet-based techniques.
 - Comprehensive feature extraction from PPG data, including systolic amplitude, diastolic amplitude, augmentation index, and statistical features.
 - Implementation of machine learning models like K-Nearest Neighbors (KNN) and Support Vector Machine (SVM).
 - Performance optimization via hyperparameter tuning using grid search and cross-validation.
# Methodology
 - **Preprocessing**: Noise reduction using PyWavelets, signal normalization with Min-Max scaling.
 - **Feature Engineering**: Extraction of 12+ features, such as mean, standard deviation, and energy metrics.
 -  **Machine Learning Models**
      - **KNN**: Optimized for Manhattan distance and varying neighbors.
      - **SVM**: Regression with kernel tuning for complex relationships.
# Datasets
 - **Source**: MIMIC database
 - **Details**: Contains 875 time points per PPG measurement and approximately 900,000 rows of data.
 - **Labels**: Systolic and diastolic blood pressure.

# Technologies Used
  -**Programming Languages**: Python
  -**Libraries**: PyWavelets, NumPy, SciPy, scikit-learn
  -**Tools**: Visualization with Matplotlib or Seaborn for signal and result analysis.
