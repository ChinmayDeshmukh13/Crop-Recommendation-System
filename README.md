# 🌱 Smart Crop Recommendation System

A **machine learning powered web application** that recommends the most suitable crop to grow based on soil nutrients and environmental conditions.

---

## 🚀 Features
- **Machine Learning Model (Random Forest)** trained on agricultural dataset.
- Predicts the best crop based on:
  - Nitrogen (N)
  - Phosphorus (P)
  - Potassium (K)
  - Temperature (°C)
  - Humidity (%)
  - pH
  - Rainfall (mm)
- **Modern Web UI** with glassmorphism design (Bootstrap + custom CSS).
- **Flask Backend API** serving ML predictions.
- **Interactive Frontend** with loading spinner and styled result card.

---

## 🛠️ Tech Stack
- **Python 3.10+**
- **Flask** (backend web framework)
- **Scikit-learn** (ML model training)
- **Pandas** (data preprocessing)
- **HTML / CSS / Bootstrap** (frontend)
- **JavaScript (Fetch API)** (AJAX requests)

---

## 📂 Project Structure
Crop_Recommendation/
-│── app.py # Flask backend
-│── crop_model.pkl # Saved ML model
-│── crop_data.csv # Dataset
-│── train_model.py # Model training script
-├── templates/
-│ └── index.html # Frontend UI
-├── static/
-│ ├── style.css # Custom styling
-│ └── script.js # Frontend logic
-└── README.md
