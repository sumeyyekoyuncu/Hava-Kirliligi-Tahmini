# Air Pollution Prediction

A machine learning web application that predicts air quality levels based on location. Users select a country and city to receive an estimated Air Quality Index (AQI) category powered by a Random Forest model trained on a global air pollution dataset.

> **Demo:** [Watch on YouTube](https://youtu.be/xjdFDcWANFg)

---

## Features

- Country and city-based AQI prediction
- Random Forest classification model
- Web interface built with Flask and HTML/CSS
- Trained on a real-world global air pollution dataset

---

## Tech Stack

| Technology | Purpose |
|---|---|
| Python | Core language |
| Flask | Web framework |
| scikit-learn | Machine learning (Random Forest) |
| pandas | Data processing |
| HTML / CSS | Frontend interface |

---

## Getting Started

### Prerequisites

- Python 3.8+
- pip

### Setup

**1. Clone the repository**

```bash
git clone https://github.com/sumeyyekoyuncu/Hava-Kirliligi-Tahmini.git
cd Hava-Kirliligi-Tahmini
```

**2. Install dependencies**

```bash
pip install flask scikit-learn pandas
```

**3. Run the application**

```bash
python app.py
```

Open your browser and navigate to `http://localhost:5000`.

---

## Dataset

The model is trained on the [Global Air Pollution Dataset](https://www.kaggle.com/datasets/hasibalmuzdadid/global-air-pollution-dataset), which contains AQI values and pollutant measurements (CO, Ozone, NO₂, PM2.5) across countries and cities worldwide.
