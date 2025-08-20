# Breast-Cancer-Prediction
This project presents a machine learning-based expert system for predicting breast cancer types (Benign, Malignant, or Normal) from mammogram images. The system integrates image segmentation, feature extraction, and classification techniques to deliver accurate and explainable predictions (IDC+ OR IDC-) that can aid in early diagnosis.

## Key Features
Segmented tumor regions using Fuzzy C-Means clustering
Extracted features using DWT, PCA, and GLCM (13 statistical texture features)
Classified images using K-Nearest Neighbors (KNN)
Applied morphological operations for tumor boundary enhancement and area estimation
Achieved an average accuracy of 92%

## Technologies Used
Python, OpenCV, NumPy, Scikit-learn, Pandas, Matplotlib
