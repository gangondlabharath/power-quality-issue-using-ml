 ⚡ Power Quality Classifier – Smart Detection Using ML
Welcome to Power Quality Classifier, your intelligent assistant for detecting and classifying power quality disturbances using cutting-edge machine learning models! Whether you're working in a research lab or an industrial setting, this project helps automate and improve how we detect key electrical issues—fast, reliable, and with high accuracy.

🚀 Key Highlights
1. Data Collection – From Simulation to Sheet
MATLAB Simulink Workspace Integration: Power quality events such as sag, swell, interruption, and harmonics are simulated using MATLAB Simulink models.

Export to Excel: Collected signals and features are exported directly from the MATLAB workspace to Excel, making the data ready for machine learning training.
📥 From simulation to spreadsheet in just a few steps!

2. Data Preprocessing – Make It ML-Ready
Label Encoding & Cleaning: Class labels are added to represent each event type, and features are cleaned for consistent formatting.

Feature Selection: Time-domain and frequency-domain features are selected to effectively distinguish between power quality issues.

Train-Test Split: The dataset is split for training and validation to ensure robust model performance.

3. Model Training & Evaluation – Know What Works
We trained and evaluated several classification algorithms to identify the best performer:

✅ Random Forest

✅ Support Vector Machine (SVM)

✅ Logistic Regression

Each model was trained using the processed dataset and evaluated using accuracy and confusion matrices.

📊 Result:
The Random Forest Classifier outperformed others, achieving the highest accuracy and reliability in classifying all types of power quality events.

🛠 Technologies Used
MATLAB Simulink – Power quality event simulation

Python (pandas, scikit-learn, matplotlib) – Data processing, model training, and evaluation

Excel – Data exchange between MATLAB and Python

Machine Learning Models – Random Forest, SVM, Logistic Regression

🧠 How It Works
Simulate Events in MATLAB: Generate power quality events (sag, swell, etc.)

Export to Excel: Save data from Simulink workspace into Excel format.

Preprocess the Data: Clean, label, and split the data using Python.

Train ML Models: Use scikit-learn to train multiple classifiers.

Evaluate Performance: Compare results and select the best-performing model.

🔮 Future Enhancements
Real-time event detection from live waveform data

Integration with embedded systems for on-site fault monitoring

GUI for model interaction and live classification

📬 Contact
Have questions or want to collaborate? Feel free to reach out via GitHub or email. Let’s power up smarter systems together!

🎉 Accurate. Automated. Intelligent. Welcome to the future of Power Quality Monitoring.
