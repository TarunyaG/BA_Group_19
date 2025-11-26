🌫️ AirAware: Machine Learning–Based Air Quality Monitoring & Prediction System

AirAware is an end-to-end machine learning project designed to monitor, classify, and forecast Air Quality Index (AQI) across Indian cities. The system integrates ML prediction, time-series forecasting, geospatial visualization, and an interactive user interface to provide real-time and future insights into air pollution.

🚀 Features

AQI Prediction Module
Predicts numerical AQI values and classifies them into categories (Good, Moderate, Poor, etc.) using Random Forest.

Time-Series Forecasting
ARIMA-based forecasting to predict future pollutant trends.

Geospatial AQI Mapping
Interactive heatmaps and state-wise AQI color maps using Folium.

Interactive Dashboard
User-friendly Gradio UI to input pollutant values, view results, maps, and forecasts.

Voice Output
AQI prediction and category read aloud using Google Text-to-Speech (gTTS).

📁 Project Structure
├── data/                          # Raw and preprocessed datasets
├── notebooks/
│   ├── air_quality_prediction.ipynb
│   └── finalhack.ipynb
├── models/                        # Saved ML models (Random Forest, ARIMA)
├── app/                           # Gradio UI files
├── maps/                          # Generated heatmaps and AQI maps
├── README.md                      # Project documentation
└── requirements.txt               # Dependencies

🧠 Models Used
🔹 Regression Models (AQI Value Prediction)

Linear Regression

Decision Tree Regressor

Random Forest Regressor (Best)

RMSE (Test): 1.15

R² (Test): 0.99989

🔹 Classification Models (AQI Category Prediction)

Logistic Regression

Decision Tree Classifier

Random Forest Classifier (Best)

Accuracy: 99.98%

Kappa Score: 0.99975

K-Nearest Neighbours (KNN)

🔹 Forecasting

ARIMA (1,1,1) model for pollutant-level prediction

📊 Business Insights

PM10 and PM2.5 are the major pollution drivers.

Industrial areas show consistently higher pollutant levels.

Forecasting enables early detection of pollution spikes.

Supports data-driven policymaking for smart cities.

Identifies monitoring infrastructure gaps across states.

Helpful for public awareness with AQI + health advisory.

Useful for industrial compliance and environmental audits.

🖥️ Tech Stack

Python

Machine Learning: Scikit-learn

Time-Series Modeling: Statsmodels (ARIMA)

Visualization: Matplotlib, Seaborn, Folium

Web UI: Gradio

Voice Engine: gTTS

Data Handling: Pandas, NumPy

⚙️ How to Run
1️⃣ Install Dependencies
pip install -r requirements.txt

2️⃣ Run the Prediction/Forecasting Notebooks
jupyter notebook air_quality_prediction.ipynb

3️⃣ Launch the Gradio App
python app/main.py

🌍 Dataset

Kaggle: Indian Air Quality Dataset (2015–2020)
Includes SO₂, NO₂, PM10, PM2.5, CO, O₃ measurements across Indian cities.

📝 Conclusion

AirAware demonstrates how machine learning, time-series analytics, and geospatial visualization can work together to build a powerful decision-support system for environmental monitoring and sustainable urban planning.

🤝 Contributors

Team 19
C2 Batch 
BL.EN.U4CSE22253, Saurab Mahuli
BL.EN.U4CSE22254, Shail Garg
BL.EN.U4CSE22259, Tarunya G
BL.EN.U4CSE22267, Gayatri Yerukola
