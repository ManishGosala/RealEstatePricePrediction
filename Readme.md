# 🏡 Real Estate Price Prediction

A full-stack machine learning web app that predicts house prices in Bengaluru based on location, square footage, number of bedrooms, and bathrooms. Built using Python, Flask, HTML/CSS/JS, and scikit-learn.

---

## 🚀 Features

- Predicts property prices based on user input
- Clean, responsive web UI
- Trained ML model on real-world Bengaluru housing dataset
- Supports multiple features like location, area, BHK, bathrooms
- Modular architecture: `client`, `server`, and `model`

---

## 🛠 Tech Stack

| Frontend     | Backend     | ML & Data    |
|--------------|-------------|--------------|
| HTML, CSS, JS| Flask (Python) | scikit-learn, Pandas, NumPy |

---

## 🧠 Model

- Trained using Linear Regression on cleaned Bengaluru housing data.
- Feature engineering done with one-hot encoding of locations.
- Serialized using `pickle` for deployment.

---

## 📁 Project Structure

Real Estate Price Prediction/
├── client/ # Frontend (HTML, CSS, JS)
├── model/ # ML model, data, and notebooks
├── server/ # Flask backend logic
└── README.md # This file

---

## ⚙️ Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ManishGosala/RealEstatePricePrediction.git
   cd RealEstatePricePrediction
2. **Install dependencies:**
    pip install -r requirements.txt
3. **Run the server:**
    cd server
    python server.py
4. **Access the app:**
    Open your browser and go to http://localhost:5000
    or open app.

---

## 📊 Dataset

- **Source:** [Bengaluru House Data](https://www.kaggle.com/datasets)
- **Original file:** `Bengaluru_House_Data.csv`
- **Cleaned version used for training:** `bhp.csv`

---

## 📎 Model Files

- `banglore_home_prices_model.pickle`  
- `columns.json`  
- CSVs used for training/testing are included in the `model/` directory:
  - `bhp.csv` (cleaned dataset)
  - `Bengaluru_House_Data.csv` (raw dataset)

---

## 📌 Contributors

- **Manish Gosala** – Adapted and modified

---




