# Deep learning approaches for seismic gamma ray prediction: insights from seismic attributes case study F3 Netherland
**Our Contributor Nungga Saputra, Arifina Resyuanti, and Haris Muhlisin**
## Overview

This project leverages machine learning techniques to forecast gamma-ray (GR) logs from seismic data, particularly in areas with limited well data. The study utilizes three machine learning models—Convolutional Neural Network (CNN), Random Forest, and K-Nearest Neighbors (KNN)—to identify complex patterns in seismic data and to analyze the intricate correlations between seismic parameters and GR logs.

## Objective

The prediction of GR logs from seismic data presents significant value in exploration and development, especially in domains lacking comprehensive well log data. However, the limited resolution of seismic data often poses challenges when trying to establish connections with GR log data in thin or complex layers. This project aims to overcome these limitations by applying machine learning (ML) methods to capture the intricate relationships between seismic attributes and GR records.

## Methods

1. **Data Preparation:**
   - Seismic data is converted into multiple attributes, such as RMS amplitude, chaos, envelope, gradient magnitude, sweetness, instantaneous frequency, dominant frequency, instantaneous bandwidth, and instantaneous quality.
   - GR logs are preprocessed and aligned with the corresponding seismic traces.

2. **Machine Learning Models:**
   - **K-Nearest Neighbors (KNN):** A non-parametric algorithm used to predict GR values by identifying the nearest neighbors in seismic attribute space.
   - **Random Forest:** An ensemble method that combines multiple decision trees to make robust predictions of GR logs based on seismic attributes.
   - **Convolutional Neural Network (CNN):** A deep learning model designed to analyze seismic amplitude data in grid format, capturing spatial patterns to accurately forecast GR logs.

3. **Model Evaluation:**
   - Each model's performance is evaluated using metrics Mean Squared Error (MSE), R2, MAE, RMSLE, and MAPE to compare their accuracy in predicting GR logs.

## Results

Among the three machine learning methods, the CNN model demonstrated superior performance, achieving the lowest error rate according to evaluation metrics. This highlights the CNN's effectiveness in capturing the complex, spatial relationships within seismic data.

## Conclusion

The findings of this research suggest that ML techniques, particularly CNN, can significantly enhance the prediction of GR logs from seismic data, providing a valuable tool for subsurface characterization in hydrocarbon exploration. This approach can be used as a benchmark for future studies and field development.

## How to Run the Project
**Requirements:**
   - Python 3.10
   - Libraries:
 ```
     Scikit-learn
     TensorFlow
     NumPy
     Pandas
     Matplotlib
     Pytorch
     Seaborn
     Segyio
     Tensorflow
     Scipy
```

