# 🌾 Crop Prediction Model

This project is focused on predicting the **most suitable crop** or **crop yield** based on various agricultural and environmental parameters using machine learning techniques. It aims to support farmers, researchers, and policy makers in making data-driven decisions for sustainable agriculture.

## 📊 Features Used

- Rainfall
- Temperature
- Humidity
- Soil Type
- pH Level
- Area Sown
- Fertilizer Usage
- Historical Crop Yield Data

## 🧠 Models Used

- Linear Regression
- Random Forest Regressor
- XGBoost Regressor
- Feature Engineering (for improving accuracy)
- Hyperparameter Tuning

## 📁 Dataset

The model is trained on a custom dataset containing real-world agricultural data. Files included:

- `crop_yield.csv` – Main dataset containing features and yield/crop type
- `01_Data_Loading_and_EDA.ipynb` – Notebook for loading data and performing exploratory data analysis
- `.ipynb_checkpoints/` – Jupyter autosave backups

## 📈 Performance Metrics

- RMSE (Root Mean Square Error)
- R² Score
- MAE (Mean Absolute Error)

## 🛠️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/rock917/crop-prediction-model.git
cd crop-prediction-model
