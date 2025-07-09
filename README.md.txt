# 🔌 Energy Consumption Forecasting using XGBoost

This project predicts hourly energy consumption based on historical data using XGBoost.

## 📌 Dataset
- Source: [UCI Individual household electric power consumption](https://archive.ics.uci.edu/ml/datasets/individual+household+electric+power+consumption)
- Fields used: `Global_active_power`, timestamp, lag features, etc.

## 📈 ML Workflow
- Data parsed into hourly aggregates
- Features: hour, day of week, month, lag_1 (previous hour’s power)
- Trained XGBoost regressor on historical data
- Evaluation: RMSE ≈ 0.546, MAE ≈ 0.375

## 🎯 Explainability
- Feature importance from XGBoost
- SHAP summary bar plot

## 🔧 Tech Stack
- Python, Pandas, XGBoost, SHAP, Scikit-learn, Matplotlib
