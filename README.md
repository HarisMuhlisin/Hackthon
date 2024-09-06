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
   - **Random Forest Regressor:** A robust ensemble learning algorithm that combines multiple decision trees to improve predictive accuracy of GR logs.
   - **ExtraTree Regressor:** An extension of the decision tree model that uses randomized decisions at each node, enhancing model diversity and reducing overfitting.
   - **Hybrid CNN + LSTM:** A deep learning approach where CNN extracts spatial features from seismic amplitude data, and LSTM layers capture temporal dependencies to predict GR logs with higher accuracy.

3. **Model Evaluation:**
   - The performance of each model is evaluated using metrics such as Mean Squared Error (MSE) to determine the most accurate method for predicting GR logs.

## Results

The hybrid CNN + LSTM model demonstrated superior performance, achieving the lowest error rate according to evaluation metrics. This suggests that the combination of spatial feature extraction and temporal dependency modeling provides the best accuracy in predicting GR logs from seismic data.

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

