# Electric Motor Temperature Prediction using Machine Learning

**Author:** Karthik  
**GitHub:** https://github.com/asadikarthik  

---

## Overview

Electric motors are widely used in industrial automation, manufacturing, and electric vehicles. Overheating can reduce efficiency, damage components, and cause unexpected failures.

This project uses Machine Learning to predict electric motor temperature using sensor and operational data. The system helps detect overheating early and supports predictive maintenance to improve reliability and reduce downtime.

---

## Objectives

- Predict motor temperature using machine learning models
- Detect overheating before motor failure occurs
- Improve motor efficiency and lifespan
- Support predictive maintenance applications
- Demonstrate a real-world industrial ML use case

---

## Machine Learning Models Used

The following regression models were implemented and evaluated:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Support Vector Machine (SVM)

These models are trained using parameters such as:

- Motor speed
- Torque
- Current
- Voltage
- Environmental and sensor data

---

## Technologies Used

**Programming Language**
- Python

**Libraries**
- Scikit-learn
- NumPy
- Pandas

**Backend**
- Flask

**Frontend**
- HTML
- CSS

**Visualization**
- Matplotlib
- Seaborn

---

## Project Structure

```
Electric-Motor-Temperature-Prediction/
│
├── Code/                      # Frontend HTML files
│   ├── index.html
│   ├── sensor.html
│   └── Manual.html
│
├── Main/                      # Backend and ML scripts
│   ├── app.py
│   ├── train_model.py
│   └── sensor_model_train.py
│
├── Output/                    # Screenshots
│   ├── Home.png
│   ├── Sensor.png
│   ├── Manual.png
│   └── Prediction_Result.png
│
├── data/                      # Dataset (not included)
├── .gitignore
└── README.md
```

---

## Features

- Machine learning based temperature prediction
- Manual input prediction interface
- Sensor-based prediction interface
- Flask web application deployment
- Multiple ML model training and comparison
- Simple and clean user interface

---

## Dataset and Model Files

The dataset and trained model files are not included in the repository due to size limitations.

Dataset used:
```
measures_v2.csv
```

To generate trained models locally, run:

```bash
python train_model.py
python sensor_model_train.py
```

---

## How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/asadikarthik/Electric-Motor-Temperature-Prediction-using-Machine-Learning.git
```

### 2. Navigate to the project folder

```bash
cd Electric-Motor-Temperature-Prediction-using-Machine-Learning/Main
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Flask application

```bash
python app.py
```

### 5. Open in browser

```
http://127.0.0.1:5000
```

---

## Applications

- Industrial motor monitoring
- Predictive maintenance systems
- Electric vehicle motor monitoring
- Smart manufacturing
- Automation systems

---

## Future Improvements

- Real-time sensor integration using IoT
- Cloud deployment
- Deep learning model implementation
- Performance optimization
- Live dashboard and analytics

---

## Conclusion

This project demonstrates how machine learning can be used to predict electric motor temperature using sensor data. It provides a complete workflow including model training, evaluation, and deployment using a Flask web application. This approach helps improve motor reliability and enables predictive maintenance in industrial environments.

---

**Developed by Karthik**  
GitHub: https://github.com/asadikarthik
