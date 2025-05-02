# 🌐 Brightness Temperature Forecasting using INSAT-3D Satellite Data

This project focuses on automating the extraction, preprocessing, and forecasting of Brightness Temperature (BT) from INSAT-3D satellite HDF5 data using Machine Learning techniques.

---

## 📌 Objective

- Extract and process `IMG_TIR1_TEMP` datasets from INSAT-3D HDF5 files.
- Engineer temporal and statistical features.
- Train regression models to predict future BT values.
- Visualize trends, residuals, and forecasting outputs.
- Build a fully automated ML pipeline for meteorological applications.

---

## 🛰️ Dataset

- **Source**: INSAT-3D Satellite (provided by ISRO)
- **Files**: 60 HDF5 files
- **Timeframe**: 30 days of data, 2 observations/day (12:15 PM and 12:45 PM)
- **Key Dataset**: `IMG_TIR1_TEMP` (Brightness Temperature Grid)

---

## 🧠 Technologies & Libraries

- **Language**: Python 3.x
- **Data Handling**: `h5py`, `numpy`, `pandas`
- **Visualization**: `matplotlib`, `seaborn`
- **Modeling**: `scikit-learn`
- **Forecasting Models**: `RandomForestRegressor`, `GradientBoostingRegressor`

---

## 📈 Machine Learning Pipeline

1. **HDF5 File Parsing**
2. **BT Feature Extraction (Median, Max, Min, Range)**
3. **Feature Engineering (Lag, Time, Rolling Stats)**
4. **Model Training & Testing**
5. **Forecasting Future BT**
6. **Performance Evaluation (R², MAE, RMSE)**
7. **Visualization of Results & Residuals**

---

## 🔍 Performance Metrics

| Model               | R² Score | MAE    | RMSE   |
|--------------------|----------|--------|--------|
| Random Forest       | ~0.9939  | ~0.0098| ~0.0181|
| Gradient Boosting   | ~1.0000  | ~0.0000| ~0.0000|

---

## 📊 Visualizations Included

- Actual vs Predicted BT plots
- Forecast trends
- Residual distributions
- Q-Q plot
- Error vs Time-of-Day plots

---

## 📂 Project Structure

