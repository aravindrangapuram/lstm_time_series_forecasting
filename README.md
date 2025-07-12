# lstm_time_series_forecasting

## Main Notebook

```
├── notebooks/                
│   ├── ;stm_forecasting.ipynb
```

## Overview
This project demonstrates how to use Long Short-Term Memory (LSTM) neural networks to perform time series forecasting on the historical monthly female births dataset. The goal is to build a model that can accurately predict the number of female births in future months based on past trends.


## Strategic Plan of Action

The project follows a structured approach to ensure accurate and reliable sales predictions:
### 1. Data Collection & Exploration
    Gather historical sales data from various stores.
    Perform exploratory data analysis to understand data distributions and identify anomalies.
    
### 2. Data Preprocessing
    Handle missing values and outliers.
    
### 3. Model Development
    Split data into training and testing sets.
    Train model using lstm and tuning it.
    Perform hyperparameter tuning using Optuna study for optimal performance.

### 4. Model Evaluation
    Evaluate models using metrics like MAE, RMSE
    Compare model performances and select the best-performing model.

## Model Accuracies
```
Train Loss: 0.0222, Validation Loss: 0.0153
--- Model Evaluation ---
Mean Absolute Error (MAE): 4.914
Root Mean Squared Error (RMSE): 6.189
```

## Conclusion
```
Model was able to learn the patterns in the data, as seen from the loss curves and the predictions. However to increase the accuracy of the model, 
We would need to add more features to the model and improvise the explanation of the data.
This could include adding more historical data, external factors, or using more complex architectures.
```

## 📬 Contact

**Aravind Reddy Rangapuran**  
📧 Email: [aravind.rangapuram@gmail.com](mailto:aravind.rangapuram@gmail.com)  
🔗 LinkedIn: [linkedin.com/in/aravind-reddy-rangapuram](https://www.linkedin.com/in/aravind-reddy-rangapuram/)
