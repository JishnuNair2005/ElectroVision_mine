# ⚡ Peak Electricity Demand Prediction

> A hybrid machine learning pipeline forecasting city-wide power consumption to optimize grid resilience, served via a dual Node/Python architecture.

**[Insert a screenshot of a data visualization graph, or the model's output prediction plot here]**

## 🧠 System Architecture
This research project tackles the challenge of predicting both long-term energy trends and sudden, volatile spikes in grid usage, integrated into a functional backend.

* **Sequence Modeling:** LSTM (Long Short-Term Memory) networks to capture sequential time-series patterns.
* **Decision Trees:** XGBoost to handle non-linear relationships and tabular feature data.
* **Backend Integration:** Node.js server handling general requests, communicating with a dedicated Python AI engine.

## ✨ Core Features
* **Hybrid Forecasting Pipeline:** Combined LSTM and XGBoost architectures to maximize the accuracy of peak demand predictions.
* **Microservice Architecture:** Separated the compute-heavy ML processing (Python) from the primary server (Node.js) for better resource management.
* **Data Pipeline:** Engineered a robust cleaning and structuring process for large-scale historical datasets to ensure high-quality model inputs.

## 🚀 How to Run Locally

1. Clone the repository:
   `git clone https://github.com/JishnuNair2005/peak-electricity-prediction.git`

2. Start the AI Engine (Python):
```bash
   # Navigate to the Python directory (update path if needed)
   pip install -r requirements.txt
   python server.py
   ```

3. Start the Main Server (Node.js):
```bash
   # Navigate to the Node directory (update path if needed)
   npm install
   node index.js
   ```
