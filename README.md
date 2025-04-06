# 🌍 AI-Powered Micro-Earthquake Pattern Recognition & Early Warning System

A serverless, real-time earthquake monitoring system that detects micro-earthquake precursors using deep learning (LSTM) and traditional ML models (Random Forest, SVM, Logistic Regression). The system includes geospatial mapping, IoT sensor simulation, and real-time prediction for early warning and anomaly detection.

---

## 📌 Features

- ✅ Deep Learning with **PyTorch (LSTM)** for precursor detection
- ✅ Real-time simulated **IoT sensor streaming**
- ✅ Traditional ML models: **Random Forest, SVM, Logistic Regression**
- ✅ **Geospatial mapping** of earthquake events with Folium
- ✅ Data preprocessing, scaling, and time-series handling
- ✅ Visualizations: heatmaps, time series plots
- ✅ Real-time prediction output per second

---

## 🧠 Machine Learning Models

| Model                  | Purpose                    | Library         |
|------------------------|----------------------------|------------------|
| LSTM                   | Sequence learning          | PyTorch          |
| Random Forest Classifier | Snapshot classification    | scikit-learn     |
| Support Vector Machine | Snapshot classification    | scikit-learn     |
| Logistic Regression    | Snapshot classification    | scikit-learn     |

---

## ⚙️ How It Works

1. Simulated IoT data stream sends real-time acceleration sensor data (X, Y, Z).
2. Buffer stores recent 50 samples (approx. 5 seconds).
3. LSTM uses full sequence for prediction.
4. Traditional ML models use the latest sensor reading.
5. Outputs are printed every second with predicted earthquake risk.
6. Historical event data is geospatially visualized.

---

## 📊 Visualizations

- **Time Series Plots** of micro-earthquakes by region
- **Seismic Heatmaps** over time
- **Interactive Map** with earthquake markers
