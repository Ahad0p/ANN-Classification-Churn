# Customer Churn Prediction with ANN

This project is a web application that predicts customer churn using an Artificial Neural Network (ANN). It is built with TensorFlow for model training and Streamlit for deployment.

## 🚀 Live Demo

Check out the deployed app here:  
👉 [Customer Churn Prediction App](https://ann-classification-churn-vzhws5n3w3lgxbh2gtykox.streamlit.app/)


## 🔍 Features

- Takes user input for customer details
- Encodes categorical variables using saved encoders
- Scales numerical data using a trained scaler
- Predicts churn using a trained Keras model (`model.h5`)
- Displays prediction result on the Streamlit web app

---

## 🛠️ Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone <your-repo-url>
   cd <project-folder>


.
├── app.py                     # Main Streamlit app
├── model.h5                   # Trained Keras model
├── scaler.pkl                 # StandardScaler
├── onehot_encoder_geo.pkl     # OneHotEncoder for 'Geography'
├── label_encoded_gender.pkl   # LabelEncoder for 'Gender'
├── requirements.txt           # Python dependencies
├── .gitignore                 # Git ignore file
└── README.md                  # Project overview


🧠 Model Info
-Trained on customer data to predict churn

-Uses a neural network built with TensorFlow/Keras

-Requires encoded and scaled input data for prediction