# 🌾 Farm Irrigation System using Machine Learning

## 📌 Project Overview

This project automates irrigation decisions using sensor data collected from various parcels in a farm. It uses a machine learning model to predict which parcels need watering based on soil sensor values. The system is designed to improve irrigation efficiency and reduce water wastage.

---

## 📂 Files Included

* `irrigation_machine.csv` – Dataset containing sensor readings and irrigation labels for different parcels.
* `Farm_Irrigation_System.pkl` – Trained machine learning model for predicting irrigation needs.
* `Irrigation_System.ipynb` – Jupyter notebook containing data analysis, visualization, and model usage.

---

## ⚙️ Features

* Calculates time intervals (daily, weekly) for scheduling.
* Visualizes sensor behavior using matplotlib.
* Identifies parcels that require irrigation.
* Predicts water needs using a trained model.
* Uses real sensor inputs for decision-making.

---

## 🚀 How to Run

1. Open `Irrigation_System.ipynb` in Jupyter or Google Colab.
2. Make sure `irrigation_machine.csv` and `Farm_Irrigation_System.pkl` are in the same directory.
3. Run all cells to view visualizations and prediction outputs.

---

## 🧠 Technologies Used

* Python
* NumPy
* Matplotlib
* Pandas
* Scikit-learn (for model training – already pickled)

---

## 📈 Use Case

This system can help farmers:

* Monitor real-time soil conditions.
* Automate irrigation timing.
* Save water and increase yield by targeting only necessary parcels.

---
