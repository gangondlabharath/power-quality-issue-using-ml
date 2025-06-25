
🔌 Power Quality Issue Classification using Machine Learning
This project focuses on detecting and classifying power quality (PQ) disturbances in electrical systems using various machine learning algorithms. Power quality events such as sags, swells, harmonics, and interruptions can cause serious disruptions in sensitive equipment and industrial processes. Early and accurate classification helps in implementing preventive measures and improving system reliability.

📌 Project Overview
The system leverages simulated or measured voltage waveform data and applies preprocessing techniques (like feature extraction in time/frequency domain) to train ML models. The primary goal is to accurately classify the type of disturbance based on learned patterns.

🛠️ Features
Classification of PQ issues: sag, swell, interruption, harmonics, transients, etc.

Dataset generated from MATLAB Simulink or sourced from open repositories.

Feature engineering using statistical and signal processing methods.

Models implemented:

Support Vector Machine (SVM)

Random Forest

K-Nearest Neighbors (KNN)

Decision Tree, etc.

📊 Results
The models are evaluated based on metrics like accuracy, precision, recall, and confusion matrix to determine classification effectiveness.

📁 Repository Structure
bash
Copy
Edit
├── data/                 # Raw and processed datasets
├── notebooks/            # Jupyter notebooks for EDA and modeling
├── models/               # Saved trained models
├── src/                  # Source code for preprocessing and training
├── results/              # Evaluation reports and plots
└── README.md             # Project overview
🧠 Applications
Smart grid monitoring

Fault detection systems

Power quality analysis in industrial automation

🤝 Acknowledgements
This project was developed as part of an academic/internship project in power systems and AI domain
