# ⚡ Forecasting Electricity Consumption in Tetuan City Using LSTM

This project focuses on forecasting electricity consumption in Tetuan City using deep learning techniques, specifically Long Short-Term Memory (LSTM) neural networks. The dataset includes environmental and power usage data collected over time, which can be used for predictive modeling and consumption analysis.

---

## 📊 Dataset Overview

**Filename**: `Tetuan City power consumption.csv`  
**Records**: ~52417  
**Format**: Time Series (Hourly data)

The dataset contains six features that describe weather conditions and power consumption in Tetuan City, providing an excellent base for forecasting electricity usage with machine learning or deep learning models.

---

## 📌 Features Explained

| Feature Name         | Description                                                                 |
|----------------------|-----------------------------------------------------------------------------|
| `Temperature`        | The ambient temperature in Celsius. Used as a key factor in consumption.    |
| `Humidity`           | Relative humidity (%). Affects cooling/heating power demands.               |
| `Wind Speed`         | Wind speed in km/h. May influence natural ventilation and weather changes.  |
| `general diffuse flows` | Diffuse solar radiation (W/m²). Related to solar energy exposure.      |
| `diffuse flows`      | Another measurement of diffuse radiation. Used in atmospheric modeling.     |
| `Zone 1 Power Consumption` | Electricity usage in residential/commercial zone 1 (kWh).       |
| `Zone 2 Power Consumption` | Electricity usage in zone 2 (kWh).                              |
| `Zone 3 Power Consumption` | Electricity usage in zone 3 (kWh).                              |

> 📝 These zones may refer to different sectors of the city (e.g., industrial, commercial, residential).

---

## 🚀 Objective

To build an LSTM-based forecasting model that:
- Predicts future electricity consumption across all 3 zones.
- Uses past environmental data and power usage history.
- Helps city planners and utility companies manage resources efficiently.

---

## 🛠️ Requirements

```bash
Python >= 3.7
pandas
numpy
matplotlib
seaborn
scikit-learn
tensorflow or pytorch (for LSTM)
