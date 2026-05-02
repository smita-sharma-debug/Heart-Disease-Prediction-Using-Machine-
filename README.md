# Heart-Disease-Prediction-Using-Machine Learning
## Project Overview

This project implements a Machine Learning model to predict the likelihood of heart disease in patients based on various health parameters.  
Using a Random Forest Classifier, the model analyzes input features to provide an early diagnosis, which can be crucial in preventive healthcare.

---

## Dataset

The dataset contains medical attributes such as age, sex, cholesterol levels, blood pressure, exercise-induced angina, and more.  
Data preprocessing includes one-hot encoding for categorical variables to ensure the model handles data correctly.  
Source: [Kaggle Heart Disease Dataset](https://www.kaggle.com/datasets/kamilpytlak/heart-cvd-dataset)

---

## Features Used

- Age  
- Sex  
- Chest Pain Type  
- Resting Blood Pressure  
- Cholesterol  
- Fasting Blood Sugar  
- Resting ECG Results  
- Maximum Heart Rate Achieved  
- Exercise Induced Angina  
- ST Depression Induced by Exercise  
- Number of Major Vessels  
- Thalassemia  

---

## How to Use

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/heart-disease-prediction.git
cd heart-disease-prediction

2. Install required packages
bash
Copy
Edit
pip install -r requirements.txt
3. Train the model
bash
Copy
Edit
python train_model.py
4. Run the Streamlit application
bash
Copy
Edit
streamlit run app.py
Project Structure
bash
Copy
Edit
heart-disease-prediction/
│
├── data/                  # Dataset files
│   └── heart.csv
├── models/                # Trained model and feature columns
│   ├── heart_model.pkl
│   └── feature_columns.pkl
├── train_model.py         # Script to train the model
├── app.py                 # Streamlit app for prediction
├── README.md              # Project documentation
├── requirements.txt       # List of dependencies
└── .gitignore             # Git ignore file
Dependencies
pandas

numpy

scikit-learn

streamlit

pickle (built-in Python library)

Contributing
Contributions, issues, and feature requests are welcome! Feel free to fork the repository and submit pull requests.
