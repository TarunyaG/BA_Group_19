# 🌫️ AirAware: Machine Learning–Based Air Quality Monitoring & Prediction System  
### Business Analytics Project – Team 19

AirAware is an end-to-end machine learning project designed to monitor, classify, and forecast Air Quality Index (AQI) across Indian cities. The system integrates ML prediction, time-series forecasting, geospatial visualization, and an interactive user interface to provide real-time and future insights into air pollution.

---

## 🚀 Features
- **AQI Prediction Module** using Random Forest  
- **Time-Series Forecasting** with ARIMA  
- **Interactive Geospatial AQI Maps** (Folium)  
- **Gradio Dashboard** for real-time predictions and visualization  
- **Voice Output** using gTTS for accessibility  

---

## 📁 Project Structure
├── data/
├── notebooks/
│ ├── air_quality_prediction.ipynb
│ └── finalhack.ipynb
├── models/
├── app/
├── maps/
├── README.md
└── requirements.txt
---

## 🧠 Models Used

### Regression Models  
- Linear Regression  
- Decision Tree Regressor  
- **Random Forest Regressor (Best Model)**  
  - RMSE (Test): 1.15  
  - R² (Test): 0.99989  

### Classification Models  
- Logistic Regression  
- Decision Tree Classifier  
- **Random Forest Classifier (Best Model)**  
  - Accuracy: 99.98%  
  - Kappa Score: 0.99975  
- KNN Classifier  

### Forecasting  
- ARIMA (1,1,1) for pollutant trend prediction  

---

## 📊 Business Insights
- PM10 and PM2.5 are the top contributors to AQI deterioration  
- Industrial zones show consistently higher pollution  
- Forecasting enables proactive planning  
- Supports policy framing for smart cities  
- Highlights gaps in monitoring infrastructure  
- Useful for health advisories and risk management  
- Helps track industrial emission patterns  

---

## 🖥️ Tech Stack
- Python  
- Scikit-learn, Statsmodels  
- Matplotlib, Seaborn, Folium  
- Gradio  
- gTTS  
- Pandas, NumPy  

---

## ⚙️ How to Run


### Run Jupyter Notebook

### Launch Gradio App

---

## 🌍 Dataset
- Kaggle – Indian Air Quality Dataset (2015–2020)

---

## 📝 Conclusion
AirAware demonstrates how analytics, machine learning, forecasting, and geospatial mapping can support environmental monitoring, public awareness, and sustainable city planning.

---

## 🤝 Contributors – Team 19

| Sl. No. | Reg. No.        | Name of the Student   |
|---------|------------------|------------------------|
| 1       | BL.EN.U4CSE22253 | Saurabh Mahuli         |
| 2       | BL.EN.U4CSE22254 | Shail Garg             |
| 3       | BL.EN.U4CSE22259 | Tarunya G              |
| 4       | BL.EN.U4CSE22267 | Gayatri Yerukola       |

---

