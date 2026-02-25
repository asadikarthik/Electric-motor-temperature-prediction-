Electric Motor Temperature Prediction using Machine Learning
Author

Karthik
GitHub: https://github.com/asadikarthik

Overview

Electric motors are essential components in industrial automation, manufacturing systems, and electric vehicles. Excessive motor temperature can reduce efficiency, accelerate component wear, and cause unexpected failures.

This project uses Machine Learning algorithms to predict electric motor temperature based on real-time and historical sensor data. The goal is to enable early fault detection and support predictive maintenance strategies to improve reliability and operational efficiency.

Objectives

Predict motor temperature using machine learning models

Detect overheating conditions before failure occurs

Improve motor lifespan and efficiency

Support predictive maintenance systems

Demonstrate real-world industrial ML application

Machine Learning Models Implemented

The following regression models were trained and evaluated:

Linear Regression

Decision Tree Regressor

Random Forest Regressor

Support Vector Machine (SVM)

These models use sensor and operational parameters such as:

Motor speed

Torque

Current

Voltage

Environmental conditions

Other operational sensor values

Technologies Used

Programming Language

Python

Machine Learning Libraries

Scikit-learn

NumPy

Pandas

Backend

Flask

Frontend

HTML

CSS

Data Visualization

Matplotlib

Seaborn

Project Structure
Electric-Motor-Temperature-Prediction/
│
├── Code/                      # Frontend files
│   ├── index.html
│   ├── sensor.html
│   └── Manual.html
│
├── Main/                      # Backend and ML scripts
│   ├── app.py
│   ├── train_model.py
│   └── sensor_model_train.py
│
├── Output/                    # Application screenshots
│   ├── Home.png
│   ├── Sensor.png
│   ├── Manual.png
│   └── Prediction_Result.png
│
├── data/                      # Dataset (not included)
├── .gitignore
└── README.md
Features

Machine learning based temperature prediction

Manual input prediction interface

Sensor-based prediction interface

Flask-based web application

Multiple ML model comparison

Clean and simple user interface

Dataset and Model Files

The dataset and trained model files are not included due to GitHub size limitations.

Dataset used:

measures_v2.csv

To train the models locally:

python train_model.py
python sensor_model_train.py

This will generate the required .pkl model files.

How to Run the Project
Step 1: Clone the Repository
git clone https://github.com/asadikarthik/Electric-Motor-Temperature-Prediction-using-Machine-Learning.git
Step 2: Navigate to Project Directory
cd Electric-Motor-Temperature-Prediction-using-Machine-Learning/Main
Step 3: Install Dependencies
pip install -r requirements.txt
Step 4: Run the Application
python app.py
Step 5: Open in Browser
http://127.0.0.1:5000
Application Use Cases

Industrial motor health monitoring

Predictive maintenance systems

Smart manufacturing environments

Electric vehicle motor monitoring

Automation and robotics systems

Future Improvements

Real-time sensor integration (IoT)

Cloud deployment (AWS, Azure, or GCP)

Deep learning model implementation

Performance optimization

Live dashboard with analytics

REST API integration

Learning Outcomes

This project demonstrates practical implementation of:

Machine Learning for predictive maintenance

Regression model training and evaluation

Flask web application deployment

End-to-end ML project development

Industrial use-case problem solving

Conclusion

This project shows how machine learning can be applied to predict electric motor temperature and help prevent failures before they occur. It provides a complete workflow including data processing, model training, and deployment through a web application, making it a strong example of applied machine learning in industrial systems.
