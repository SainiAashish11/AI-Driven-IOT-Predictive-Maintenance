# AI-Driven-IOT-Predictive-Maintenance - A Cognitive Twin
An Industrial IoT edge dashboard that simulates a Cognitive Digital Twin for aerospace assets. It utilizes time-series modeling to calculate Remaining Useful Life (RUL) and integrates the Google Gemini LLM API to automatically generate root-cause diagnostics from high-frequency telemetry anomalies.


![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-1.x-FF4B4B)
![Gemini AI](https://img.shields.io/badge/Generative%20AI-Google%20Gemini-8A2BE2)

## 🚀 Key Features

* **Predictive Analytics (RUL Forecasting):** Calculates equipment degradation and Remaining Useful Life using a rolling 20-cycle window across 21 sensor variables.
* **Generative AI Diagnostics:** Integrates Google Gemini API to instantly synthesize 8 cycles of multivariate telemetry into structured root-cause analysis reports upon anomaly detection.
* **Dynamic Stress Simulation:** Features an operational load multiplier (10%-100%) that scales asset degradation, reliably triggering early preventive alerts at 88% of the 8145 RPM critical failure limit.
* **IoT Edge Gateway:** A Streamlit-based dashboard rendering live sensor data, Altair visualizations, and a mathematically driven SVG fan animation at 60 FPS.

## 🛠️ Tech Stack

* **Language:** Python
* **Data Processing:** Pandas, NumPy
* **AI/ML:** Google Generative AI API (Gemini 1.5 Pro/Flash)
* **Frontend/Edge:** Streamlit, Altair (Data Visualization)
* **Dataset:** NASA CMAPSS Turbofan Engine (FD001)

## ⚙️ Installation and Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/SainiAashish11/AI-Driven-IOT-Predictive-Maintenance.git
   cd AI-Driven-IOT-Predictive-Maintenance
