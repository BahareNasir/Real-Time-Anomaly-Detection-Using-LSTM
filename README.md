# Real-Time-Anomaly-Detection-Using-LSTM
LSTM-based Regression for Time Series
# 📊 Time Series Regression using LSTM Neural Networks

This repository presents a deep learning-based time series regression model using **Long Short-Term Memory (LSTM)** networks. The model is designed to capture temporal dependencies in multivariate data for accurate prediction of continuous output variables.

## 🔍 Project Overview

The LSTM regression model was trained on sequential data with 5 input features and 2 output targets. The model architecture includes stacked LSTM layers, dropout, and fully connected layers optimized for robust prediction.

### Key Features:
- LSTM layers capture long-term dependencies
- Regression model for predicting 2 output variables
- Window-based sequence generation from tabular time series
- Evaluation metrics: MSE, MAE, R-squared

## 📊 Methodology

1. **Data Preparation**
   - Feature scaling (Min-Max & Z-score normalization)
   - Sliding window sequence creation
   - Train-test split (80/20)

2. **Model Architecture**
   - Sequence Input Layer
   - Flatten Layer
   - Two stacked LSTM layers (64, 32 units)
   - Dropout layer for regularization
   - Fully connected layers with Leaky ReLU
   - Final regression output layer (2 targets)

3. **Training Configuration**
   - Optimizer: Adam
   - Loss: MSE
   - Early stopping with validation patience
   - Epochs: 100, Mini-batch size: 16

4. **Evaluation**
   - MSE: 0.17558
   - MAE: 0.32689
   - R²: 0.98836
   - RMSE (Validation): 0.64884

## 📊 Results & Visualization

- Excellent fit between actual and predicted values
- Performance tracked with training plots
- Prediction plots for both outputs show high alignment
- Model analysis via layer-by-layer inspection

## 🧪 Technologies Used

- MATLAB
- Deep Learning Toolbox
- LSTM Network (custom architecture)

## 🚀 Future Enhancements

- Apply to real-time data streaming
- Integrate with hybrid models (e.g., LSTM + Attention)
- Deployment via embedded systems or cloud APIs

---

## 📬 Contact

For questions or collaboration:  
**Bahare Nasir**  
**Email:** bahare.na@hotmail.com

