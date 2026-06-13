Medical Insurance Cost Analysis and Prediction System

A machine learning-based web application that analyzes medical insurance data and predicts insurance costs based on user input such as age, BMI, smoking status, region, and other health-related factors.

 Project Overview

The Medical Insurance Cost Analysis and Prediction System helps users estimate their insurance charges using trained machine learning models. It also provides insights into how different factors influence insurance costs.

This project combines data analysis + machine learning + web interface to deliver an interactive prediction system.

 Features
 Data analysis of insurance dataset
 Machine Learning model for cost prediction
 User input form for predictions
 Visualization of key factors affecting insurance cost
 Simple web interface (HTML/CSS/JS or Flask/Streamlit)
 Fast real-time prediction
 Technologies Used
Python 
Pandas & NumPy
Scikit-learn
Matplotlib / Seaborn
Flask / Streamlit (optional for web app)
HTML, CSS, JavaScript (frontend if used)
 Project Structure
medical-insurance-prediction/
│
├── dataset/
│   └── insurance.csv
│
├── model/
│   └── trained_model.pkl
│
├── static/
│   ├── style.css
│   └── script.js
│
├── templates/
│   └── index.html
│
├── app.py
├── train_model.py
├── requirements.txt
└── README.md
 Installation & Setup
1. Clone the repository
git clone https://github.com/your-username/medical-insurance-prediction.git
cd medical-insurance-prediction
2. Create virtual environment (optional)
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
3. Install dependencies
pip install -r requirements.txt
 Run the Application
If using Flask:
python app.py

Then open:

http://127.0.0.1:5000
 Input Features

The model considers the following inputs:

Age
Gender
BMI (Body Mass Index)
Number of children
Smoking status
Region
 How It Works
Dataset is cleaned and analyzed
Features are encoded and preprocessed
Machine learning model is trained (Linear Regression / Random Forest)
Model is saved as .pkl
Web app takes user input and predicts insurance cost
 Example Prediction
Age: 28
BMI: 26.5
Smoker: Yes
Region: Southeast

 Predicted Insurance Cost: $12,450
 Future Improvements
Add Deep Learning model
Improve UI with React.js
Deploy on cloud (Heroku / Render / AWS)
Add user login system
Real-time data updates

 Author
S.Tharun sasi
