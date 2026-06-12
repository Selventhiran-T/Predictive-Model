# AI-Based Network Threat Detection using Machine Learning

## Project Overview

This project focuses on **Predictive Modelling for Network Threat Detection** using **Artificial Intelligence and Machine Learning** techniques. The system analyzes network traffic data to identify potential cyber threats such as intrusions, malware, and anomalies.

The goal of this project is to improve **cybersecurity by detecting suspicious activities in network traffic** and enabling proactive threat prevention.

---

## Objectives

* Detect cyber threats in network traffic using machine learning
* Analyze and visualize network traffic patterns
* Compare multiple ML models for threat detection
* Build an efficient predictive model for cybersecurity analysis

---

## Project Workflow

### 1. Data Preprocessing

* Cleaning the dataset
* Handling missing values
* Feature selection
* Data transformation

### 2. Data Visualization

* Graphical analysis of network traffic
* Understanding patterns and anomalies

### 3. Model Training

The following machine learning models were implemented:

* **BNC – BernoulliNB Classifier**
* **ADC – AdaBoost Classifier**
* **RFC – Random Forest Classifier**

### 4. Model Evaluation

* Accuracy comparison
* Performance analysis

### 5. Prediction System

Detects potential cyber threats from network data.

---

## Project Structure

```
Network-Threat-Detection/
│
├── M1-DATA PREPROCESSING.ipynb        # Notebook for cleaning & preparing the dataset
├── M2-DATA VISUALIZATION.ipynb        # Notebook for plotting charts and exploring data
├── M3-BNC.ipynb                       # Notebook implementing BernoulliNB Classifier Algorithm(BNC)
├── M4-ADC.ipynb                       # Notebook for AdaBoost Classifier Algorithm(ADC)
├── M5-RFC.ipynb                       # Notebook for Random Forest Classifier Algorithm(RFC)
├── M6-Report.ipynb                    # Notebook compiling results & summary
│
├── cyber_dataset.csv                   # Raw dataset with network traffic / threat data
├── requirements.txt                    # Python dependencies (libraries to install)
│
├── README.md                           # Project overview & usage instructions
├── .gitignore                          # Git ignore rules
├── .gitattributes                      # Git attributes
│
└── deploy/                             # Deployment / web app folder
    ├── user_management/                # Likely contains authentication, registration, and role management
    ├── users/                          # Possibly user-related views, templates, and endpoints
    └── manage.py                      # Main deployment script (probably runs server and manages user requests)
```

---

## Note About the Basic Report

The original Basic_report.html file is too large to upload directly to GitHub (338 MB exceeds the 100 MB limit).

To include it in the repository, it has been compressed as ```Basic_report.zip```.

## How to Use the Report

1. Download or clone the repository.

2. Navigate to the folder:
```
Deploy/users/templates/app/
```
3. Unzip the file:
```
unzip Basic_report.zip -d Deploy/users/templates/app/
```
4. Once unzipped, your program can access and use ```Basic_report.html``` as intended.

---

---

## Technologies Used

* Python
* Machine Learning
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Django (for deployment)

---

## Installation

Clone the repository

```
git clone https://github.com/DH4N453K4R4N/network-threat-detection.git
```

Navigate to the project folder

```
cd network-threat-detection
```

Install required libraries

```
pip install -r requirements.txt
```

Run the notebooks using **Jupyter Notebook**.

---

### Quick Start
To get this project up and running locally on your computer follow the following steps.
1. Set up a python virtual environment
2. Run the following commands
```
$ pip install -r requirements.txt
$ python manage.py migrate
$ python manage.py createsuperuser
$ python manage.py runserver
```
   
3. Open a browser and go to http://localhost:8000/

---

---

## Results

The machine learning models analyze network traffic data and classify it into **normal or malicious activities**, helping identify potential cyber threats.

---

## Applications

* Network security monitoring
* Intrusion detection systems
* Cybersecurity research
* Threat analysis in enterprise networks

---

## Author

Final Year Project – **Predictive Modelling for Network Threat Detection**


