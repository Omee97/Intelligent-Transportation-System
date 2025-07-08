# 🚦 Intelligent Transportation System (ITS)

An AI-powered, real-time traffic prediction system built using **Machine Learning** and **Deep Learning** models. This project predicts **travel time**, **average speed**, and **congestion levels** using real-world data via the **TomTom API** and displays results on interactive maps. It also includes a **Streamlit web interface** for easy user interaction.

---

## 📌 Table of Contents

- [📖 Project Overview](#-project-overview)
- [🎯 Key Features](#-key-features)
- [🧠 Models Implemented](#-models-implemented)
- [📂 Project Structure](#-project-structure)
- [⚙️ Installation & Setup](#️-installation--setup)
- [🚀 Running the Project](#-running-the-project)
- [📊 Visualizations](#-visualizations)
- [🌐 API Integration](#-api-integration)
- [📈 Sample Results](#-sample-results)
- [🛠️ Future Enhancements](#️-future-enhancements)
- [🙌 Contributions](#-contributions)
- [📄 License](#-license)
- [📬 Contact](#-contact)

---

## 📖 Project Overview

This Intelligent Transportation System (ITS) predicts real-time and future traffic conditions using:
- Live traffic data
- ML/DL algorithms
- Spatial-temporal features

It provides actionable predictions like:
- ⏱️ Travel time between any two points
- 🚦 Congestion likelihood
- 🚗 Average traffic speed

---

## 🎯 Key Features

- 🔮 Predict travel time, speed, and congestion
- 📅 Analyze traffic patterns by day, hour, and weekends
- 🌍 Integrate real-time data via TomTom API
- 🗺️ Visualize on maps using Folium and Plotly
- 🧪 Train multiple ML/DL models for comparison
- 🖥️ User-friendly web interface via Streamlit

---

## 🧠 Models Implemented

| Model              | Task                         | Description                                 |
|-------------------|------------------------------|---------------------------------------------|
| XGBoost            | Travel time prediction       | High-performance, fast, and interpretable   |
| LSTM               | Time-series prediction       | Captures sequential patterns in traffic     |
| GCN (Graph NN)     | Spatial road modeling        | Learns from road network structure          |
| Linear Regression  | Baseline estimator           | Simple but effective starting point         |

---

## 📂 Project Structure

├── Intelligent_transportsystem.ipynb # Main Notebook
├── app/
│ └── transport_app.py # Streamlit Web App
├── models/
│ ├── lstm_model.py # LSTM Code
│ └── gcn_model.py # GCN Code
├── utils/
│ └── preprocessing.py # Cleaning & Feature Engineering
├── data/
│ └── traffic_data.csv # Sample Dataset
├── outputs/
│ └── model_results.csv # Metrics and Logs
├── requirements.txt # Dependencies
└── README.md # Project Documentation

| API             | Purpose                            |
| --------------- | ---------------------------------- |
| TomTom Routing  | Predict travel time between points |
| TomTom Traffic  | Get congestion and flow details    |
| Geopy/Nominatim | Geocode locations to coordinates   |

**SAMPLE RESULTS**
| Metric            | Value         |
| ----------------- | ------------- |
| MAE (Travel Time) | 17.52 minutes |
| XGBoost Accuracy  | 94.7%         |
| LSTM RMSE         | 12.3 mins     |
| Congestion F1     | 0.91          |



Author: Kumar Shantanu
GitHub: @Omee97
Email: shantanuk0891@gmail.com 
