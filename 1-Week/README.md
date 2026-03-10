# 🌱 Smart Irrigation System

A **Machine Learning based Smart Irrigation System** that predicts optimal irrigation requirements using environmental and soil parameters.
The project uses a **multi-output regression model** to estimate irrigation needs based on temperature, humidity, soil moisture, rainfall, and pH levels.

---

# 📦 Project Structure

```
Smart-Irrigation-System
│
├── Smart_Irrigation_updated.ipynb
├── irrigation_machine.csv
├── min_max_scaler.joblib
├── multi_output_irrigation_model.joblib
└── README.md
```

**Files Description**

* **Smart_Irrigation_updated.ipynb** – Jupyter Notebook for data preprocessing, model training, and evaluation
* **irrigation_machine.csv** – Dataset containing soil and weather parameters
* **min_max_scaler.joblib** – Saved Min-Max Scaler for feature scaling
* **multi_output_irrigation_model.joblib** – Trained Multi-Output Regression Model
* **README.md** – Project documentation

---

# 📌 Features

* Data preprocessing and feature scaling using **MinMaxScaler**
* Multi-output regression model for predicting irrigation parameters
* Structured dataset with soil and climate factors
* Model serialization using **joblib**
* Model evaluation using standard regression metrics

---

# 🧠 Machine Learning Techniques Used

**Min-Max Scaling**
Normalizes input features to improve model performance.

**Multi-Output Regression**
Predicts multiple irrigation-related outputs simultaneously.

**Model Serialization**
Uses `joblib` to save and load trained models and scalers.

---

# 📂 Dataset Description

The dataset (`irrigation_machine.csv`) includes the following features:

| Feature        | Description              |
| -------------- | ------------------------ |
| Temperature    | Ambient temperature (°C) |
| Humidity       | Relative humidity (%)    |
| Moisture Level | Soil moisture content    |
| pH             | Soil pH level            |
| Rainfall       | Rainfall (mm)            |

**Output Variable**

* Optimal irrigation quantity required for crops.

---

# 🚀 How to Run the Project

### 1️⃣ Clone the repository

```
git clone https://github.com/your-username/smart-irrigation-system.git
cd smart-irrigation-system
```

### 2️⃣ Install dependencies

```
pip install pandas numpy scikit-learn joblib matplotlib
```

### 3️⃣ Run the Jupyter Notebook

Open the notebook:

```
Smart_Irrigation_updated.ipynb
```

using **Jupyter Notebook** or **JupyterLab**.

---

# 📊 Model Evaluation

The model performance is evaluated using:

* **Mean Absolute Error (MAE)**
* **Mean Squared Error (MSE)**
* **R² Score**

These metrics help measure the accuracy of irrigation predictions.

---

# 💡 Future Improvements

* Integration with **IoT sensors** for real-time data collection
* Deployment as a **web or mobile application**
* Support for **multiple crop types and regions**
* Real-time irrigation recommendations

---

# 👩‍💻 Author

**Akanksha Kalamadugu**
B.Tech – Artificial Intelligence & Machine Learning
Malla Reddy Engineering College for Women


