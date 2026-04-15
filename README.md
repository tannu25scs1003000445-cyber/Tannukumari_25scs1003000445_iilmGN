🏥 AI-Powered Health Predictor: 
Cancer & BP Monitoring📖 IntroductionEarly detection is the most critical factor in treating chronic diseases. This project presents an integrated predictive framework designed for early warning signals of Cancer Risk and Hypertension (Blood Pressure). By utilizing machine learning, we aim to assist medical professionals in timely intervention and reduce severe health complications.



 FeaturesDual-Stream Prediction: 
 
 Separate modules for estimating cancer likelihood and BP levels.Multi-Modal Data: Processes clinical, lifestyle, and genetic biomarkers.Cuffless BP Estimation: Utilizes physiological signals like PPG and ECG for non-invasive monitoring.Integrated Dashboard: A user-friendly interface to display health insights and risk scores


 
 🛠️ Tech Stack & Methodology
Software Tools

Core: Python, TensorFlow, Scikit-Learn.


Datasets: Breast Cancer Wisconsin, TCGA (via GDC Portal), and PhysioNet/MIMIC for BP signals.



Architecture 


Data Collection: Gathering medical images (MRI/CT) and vital sign signals.


Preprocessing: Noise removal, normalization, and handling data imbalance.


Feature Extraction: CNNs for image features and signal processing for PTT (Pulse Transit Time).


Modeling: * Cancer: Random Forest, XGBoost, and CNN.



BP: LSTM and Transformers for time-series forecasting.



Hardware Requirements (Conceptual) 



Sensors: MAX30102 (PPG), AD8232 (ECG).



Processors: NVIDIA Jetson Nano or high-performance GPU for real-time inference.


📊 Evaluation Metrics
The models are evaluated on the following performance indicators:


Accuracy & F1-Score: For cancer classification.


MAE (Mean Absolute Error):
For BP regression.

Model	Technique	Estimated Performance
Cancer Detection	CNN / Random Forest	
~89% - 95% Accuracy 

BP Prediction	LSTM / SVM	
~4.2 - 5 mmHg MAE 

🔮 Future Scope

Wearable Integration: Real-time data sync with smartwatches.


Deep Learning: Moving toward self-supervised models for better feature extraction.


Mobile App: Developing a cross-platform mobile health dashboard.

✍️ Project Information

Author: Tannu Baby 


Roll No: 25scs1003000445 


University: IILM University 


Supervisor: Mr. Shobhit Agrawal 

