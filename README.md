# 🌡️ BMP Prediction — Atmospheric Pressure & Altitude Forecasting

A machine learning-powered system that uses BMP sensor data collected via a UAV (quadcopter) 
to predict barometric pressure and altitude with over 80% accuracy.

---

## 📌 Overview

This project combines hardware and software to build a predictive atmospheric modeling system.
A BMP sensor mounted on a custom-built quadcopter collects real-time environmental data,
which is then fed into a trained ML model to forecast barometric pressure and altitude values.

The project was presented at the **ICASDIGT-2024 Conference** at Assam downtown University.

---

## 🚀 Features

- Real-time atmospheric data collection via BMP sensor on a UAV
- Machine learning model trained on sensor readings for pressure & altitude prediction
- Data visualization using Matplotlib
- Achieves **80%+ prediction accuracy**
- Modular pipeline: data collection → preprocessing → training → prediction

---

## 🛠️ Tech Stack

| Category        | Tools / Libraries                          |
|-----------------|--------------------------------------------|
| Language        | Python                                     |
| ML & Data       | Scikit-learn, NumPy, Pandas                |
| Visualization   | Matplotlib                                 |
| Hardware        | BMP Sensor, ESP Module, Quadcopter (UAV)   |

---

## 📂 Project Structure
```
BMP-prediction/
│
├── data/                   # Raw and processed sensor data
├── models/                 # Trained ML model files
├── notebooks/              # Jupyter notebooks for EDA and training
├── src/
│   ├── data_collection.py  # BMP sensor data ingestion
│   ├── preprocess.py       # Data cleaning and feature engineering
│   ├── train.py            # Model training script
│   └── predict.py          # Prediction and evaluation
├── visuals/                # Matplotlib plots and charts
├── requirements.txt
└── README.md
```

---

## ⚙️ Setup & Installation

1. **Clone the repository**
```bash
   git clone https://github.com/Jiasha-nath/BMP-prediction.git
   cd BMP-prediction
```

2. **Install dependencies**
```bash
   pip install -r requirements.txt
```

3. **Run the prediction pipeline**
```bash
   python src/predict.py
```

---

## 📊 Results

- **Model Accuracy:** 80%+
- **Target Variables:** Barometric Pressure, Altitude
- **Input Features:** Raw BMP sensor readings (temperature, pressure, altitude)

---

## 📄 Publication

This project was published at the **ICASDIGT-2024 Conference**, Assam downtown University.

🔗 [View Article on ResearchGate](https://www.researchgate.net/profile/Amit_Kumar915/publication/392517186_AdtU_Conference_ICASDIGT-2024_Article_Book/links/68467e92c33afe388acaf965/AdtU-Conference-ICASDIGT-2024-Article-Book.pdf#page=319)

---

## 👤 Author

**Jiasha Nath**  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-jiasha--nath-blue?logo=linkedin)](https://www.linkedin.com/in/jiasha-nath-523b79211)  
[![Email](https://img.shields.io/badge/Email-jiasha.nath.adtu@gmail.com-red?logo=gmail)](mailto:jiasha.nath.adtu@gmail.com)

---

## 📜 License

This project is licensed under the MIT License.
