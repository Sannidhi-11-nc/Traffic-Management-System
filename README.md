# Traffic Management System 🚦

This project is a smart **Traffic Management System** that uses real-time data, machine learning models, and a user-friendly interface to manage traffic congestion, predict patterns, reserve parking slots, and assist in emergency vehicle routing.

---

## 📁 Project Structure

### 🔸 Web Application Components
- `app.py` – Main Flask backend server
- `*.html` – Front-end templates (Admin, Customer, Map, Predict, etc.)
- `*.pyc` – Compiled Python cache file
- `Newdatabase.sql` – SQL file for database schema

### 🔸 Machine Learning Models
- `final.py` – Script for prediction and traffic analysis
- `a.py` – Additional logic or ML utilities
- `decision_tree_model.pkl` – Trained Decision Tree model
- `best_emergency_vehicle_model.pt` – PyTorch model for emergency vehicle routing
- `feature_names.pkl` – Pickled list of features used in ML models

### 🔸 Datasets
- `traffic.csv`
- `traffic_data_pune.csv`
- `TrafficTwoMonth.csv`

### 🔸 Images
- `frame1.jpg` to `frame15.jpg` – Sample traffic image frames for detection/analysis

### 🔸 Documents
- `capstone.pdf` – Capstone project report
- `traffic management Viva Voice.pptx` – Presentation slides

---

## 🚀 Features

- 📍 Real-time traffic data prediction
- 🚗 Emergency vehicle routing optimization using ML
- 🅿️ Smart parking reservation system
- 👥 Admin and customer login interfaces
- 📊 Visualization of traffic patterns on maps
- 🧠 Integrated ML models for accurate forecasting

---

## ⚙️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Sannidhi-11-nc/Traffic-Management-System.git
   cd Traffic-Management-System
