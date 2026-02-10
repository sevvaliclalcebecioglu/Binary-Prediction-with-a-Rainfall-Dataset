# 🌧️ Rainfall Prediction with Machine Learning

This project predicts rainfall occurrence using meteorological data and machine learning models.

## 📊 Dataset
The dataset consists of atmospheric pressure, temperature metrics, humidity, cloud coverage, sunshine duration, wind information, and engineered features.

## 🎯 Target
- **rainfall** (Binary Classification)
  - 0 → No Rain
  - 1 → Rain

## 🧠 Models
- Logistic Regression  
- Decision Tree  
- Random Forest  
- Gradient Boosting  
- AdaBoost  
- LightGBM  
- XGBoost  
- CatBoost  

Evaluation metric: **ROC-AUC**

## 🛠️ Feature Engineering
- Temperature difference  
- Humidity & cloud interaction  
- Sunshine ratios  
- Wind power  
- Cyclical day features  

## 🏆 Best Model
- **LightGBM** (after cross-validation & hyperparameter tuning)

## 💾 Saved Artifacts
```python
final_model.pkl        # Trained model
model_features.pkl     # Feature list
