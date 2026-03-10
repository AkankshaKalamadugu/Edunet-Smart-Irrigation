Project Structure
📦 Smart Irrigation System
│
├── Smart_Irrigation_updated.ipynb     # Jupyter Notebook for data preprocessing, model training, and evaluation
├── irrigation_machine.csv             # Dataset containing soil and weather parameters
├── min_max_scaler.joblib              # Saved Min-Max Scaler for consistent feature scaling
├── multi_output_irrigation_model.joblib  # Trained Multi-Output Regression Model
└── README.md                          # Project documentation


📌 Features
📊 Data preprocessing and feature scaling using MinMaxScaler

🔢 Multi-output regression model for predicting multiple irrigation parameters

📁 Clean and structured dataset with soil and climate factors

💾 Model and scaler serialization using joblib

📈 Evaluation metrics to assess model accuracy



🧠 Machine Learning Techniques Used
MinMax Scaling: For normalizing input features.

Multi-Output Regression: To predict multiple irrigation-related outputs simultaneously.

Model Serialization: Using joblib to save and load the model and scaler.


📂 Dataset Description (irrigation_machine.csv)
The dataset includes:

Feature	Description
Temperature	Ambient temperature in Celsius
Humidity	Relative humidity in percentage
Moisture Level	Soil moisture content
pH	pH level of the soil
Rainfall	Rainfall in mm
Output Variables	Optimal irrigation quantities/needs



🚀 How to Run
Clone the repository

bash
Copy
Edit
git clone https://github.com/your-username/smart-irrigation-system.git
cd smart-irrigation-system
Install dependencies

bash
Copy
Edit
pip install pandas numpy scikit-learn joblib matplotlib
Run the Jupyter Notebook
Open Smart_Irrigation_updated.ipynb using Jupyter Notebook or JupyterLab.

Test the model
Load the saved model and scaler:

python
Copy
Edit
from joblib import load
model = load('multi_output_irrigation_model.joblib')
scaler = load('min_max_scaler.joblib')
📊 Model Evaluation
The notebook includes model evaluation using metrics such as:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R² Score

These metrics help understand how well the model is performing in predicting irrigation needs.

💡 Future Improvements
Integrate with IoT sensors for real-time data

Deploy as a web or mobile application

Add support for multiple crop types and regions


🙋‍♀️ Author
Kalamadugu Akanksha
B.Tech - Artificial Intelligence & Machine Learning
Malla Reddy Engineering College for Women

