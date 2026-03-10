# 💧 Smart Farm Irrigation System using Machine Learning

This project aims to automate and optimize irrigation for farms using a machine learning model. It predicts whether irrigation is required based on environmental data and integrates with a Flask-based API for real-time predictions.

## 🚀 Project Overview

Smart irrigation reduces water wastage and ensures better crop health by using data-driven decisions. The system includes:

- A trained machine learning model (`Farm_Irrigation_System.pkl`)
- A Flask API (`app.py`) for real-time inference
- An analysis and training notebook (`Irrigation_System.ipynb`)
- Input dataset (`irrigation_machine.csv`)

## 📁 Repository Contents

| File / Folder                | Description                                                |
|-----------------------------|------------------------------------------------------------|
| `app.py`                    | Flask API to serve predictions from the trained model.     |
| `Farm_Irrigation_System.pkl`| Trained machine learning model using classification.       |
| `irrigation_machine.csv`    | Dataset used to train and test the model.                  |
| `Irrigation_System.ipynb`   | Jupyter notebook for data analysis and model training.     |

## 🧠 Model Overview

- **Goal:** Predict if irrigation is required (Yes/No) based on features such as humidity, temperature, soil moisture, etc.
- **Algorithm:** [Specify if known, e.g., Random Forest / Logistic Regression]
- **Accuracy:** [Add accuracy or performance metrics if available from your notebook]

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/smart-irrigation-system.git
cd smart-irrigation-system
````

### 2. Create Virtual Environment (optional but recommended)

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

If `requirements.txt` is not present, install manually:

```bash
pip install flask pandas scikit-learn numpy
```

### 4. Run the Flask API

```bash
python app.py
```

The server will run at `http://127.0.0.1:5000/`

## 📬 API Usage

### Endpoint

```http
POST /predict
```

### Sample Input (JSON)

```json
{
  "temperature": 30,
  "humidity": 75,
  "soil_moisture": 25,
  "ph": 6.5,
  "rainfall": 50
}
```

### Sample Output

```json
{
  "irrigation_required": "Yes"
}
```

## 📊 Dataset Description (`irrigation_machine.csv`)

| Feature        | Description           |
| -------------- | --------------------- |
| temperature    | Temperature in °C     |
| humidity       | Humidity in %         |
| soil\_moisture | Soil moisture level   |
| ph             | Soil pH level         |
| rainfall       | Rainfall in mm        |
| irrigation     | Target label (Yes/No) |

## 📓 Jupyter Notebook

* EDA (Exploratory Data Analysis)
* Feature engineering
* Model training and evaluation
* Model serialization (`pkl` file)

## 📌 Future Enhancements

* Integration with IoT devices for real-time sensing
* Deployment on cloud (Heroku/AWS)
* Mobile or web dashboard for farmers

## 🙌 Acknowledgments

* Dataset inspired by agricultural IoT practices
* Model training and deployment guided by ML & AI principles

## 🧑‍💻 Author

**Akanksha Kalamadugu**
B.Tech, Artificial Intelligence & Machine Learning
Malla Reddy Engineering College for Women

---
