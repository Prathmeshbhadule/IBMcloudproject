# Power System Fault Detection and Classification

## 🔍 Project Overview
This project focuses on building a machine learning-based system to detect and classify different types of faults in a power distribution network using real-time voltage and current phasor data. The model aims to identify faults such as line-to-ground (LG), line-to-line (LL), double line-to-ground (DLG), and three-phase (LLL) faults, helping utilities maintain grid stability and reliability.

## 🎯 Objective
- Accurately detect and classify power system faults in real-time
- Enable proactive maintenance and reduce outage durations
- Support scalability through IBM Cloud-based deployment

## 🛠 Technologies Used
- **IBM Watson Studio** – Model development and training  
- **IBM Watson Machine Learning** – Model deployment  
- **IBM Cloud Object Storage** – Data storage  
- **IBM Event Streams (Kafka)** – Real-time data streaming  
- **IBM Cognos Analytics** – Visualization and dashboards  
- **Python, scikit-learn, XGBoost, Flask** – Model and API development

## 📦 Project Structure
├── data/ # Raw and processed datasets
├── notebooks/ # IBM Watson Studio notebooks
├── model/ # Trained model files (.pkl)
├── app/ # Flask API for model inference
├── dashboard/ # Visualization setup (Cognos/Grafana)
└── README.md # Project documentation

markdown
Copy
Edit

## ⚙️ Algorithm Workflow
1. **Data Collection** – Real-time and historical data from IEDs, PMUs, SCADA  
2. **Preprocessing** – Cleaning, normalization, feature extraction  
3. **Modeling** – Train classifier (e.g., Random Forest, XGBoost)  
4. **Evaluation** – Accuracy, Precision, Recall, F1-Score  
5. **Deployment** – IBM Cloud REST API for live fault detection  
6. **Alerting** – Auto-alerts via email/SMS using IBM Cloud Functions

## 🚀 Deployment Instructions
1. Upload code and data to IBM Watson Studio project.
2. Train and deploy model using Watson Machine Learning.
3. Set up real-time input stream using IBM Event Streams.
4. Build dashboard with IBM Cognos Analytics.
5. Integrate alert system with IBM Cloud Functions.

## 📈 Future Scope
- IoT integration for real-time phasor monitoring
- Use of deep learning models (LSTM/CNN) for complex fault patterns
- Grid automation integration for rapid fault isolation
- Scalable monitoring of multiple substations via centralized dashboard

## 🤝 Contributors
- **Prathmesh Bhadule** – Developer  
- IBM Cloud Services
