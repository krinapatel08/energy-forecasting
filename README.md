# 🔌 Energy Consumption Forecasting using XGBoost

This project predicts hourly energy consumption based on historical data using XGBoost.

## 📂 Dataset

Due to GitHub’s file size limit, the dataset is not uploaded here.

Please manually download the dataset from this source:

[UCI Power Consumption Dataset](https://archive.ics.uci.edu/ml/datasets/individual+household+electric+power+consumption)

Once downloaded, place it as:


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
