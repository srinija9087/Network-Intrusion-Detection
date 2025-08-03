# Network-Intrusion-Detection
IBM Cloud Project on Network Intrusion Detection using Machine Learning

# Problem Statement
Create a robust network intrusion detection system (NIDS) using machine learning. The
system should be capable of analyzing network traffic data to identify and classify various
types of cyber-attacks (e.g., DoS, Probe, R2L, U2R) and distinguish them from normal
network activity. The goal is to build a model that can effectively secure communication
networks by providing an early warning of malicious activities.

# Dataset
Kaggle Dataset Link: https://www.kaggle.com/datasets/sampadab17/networkintrusion-detection

Dataset Description:
The dataset consists of simulated network traffic data containing 41 features per record. These features capture various aspects of the traffic such as:

Basic features (e.g., protocol, service, duration)
Content features (e.g., number of failed logins, root access)
Traffic features (e.g., number of connections in past 2 seconds)
Label: Each record is labeled either as "normal" or with a specific attack type (e.g., neptune, smurf, satan, etc.)

For simplicity, all attack types were grouped into the following categories:

DoS – Denial of Service
Probe – Surveillance and Probing
R2L – Remote to Local
U2R – User to Root
Normal – Legitimate traffic

# Prediction Process:
Real-time prediction enabled using IBM Watson Studio.
Model deployed as an API endpoint for integration into real-world systems.

Model predicts:

- normal – Safe connection
- anomaly – Possible attack

# Conclusion
The proposed ML-based NIDS system successfully detects network intrusions with high accuracy and low false positives. By learning from past attack patterns, the system is more adaptable than traditional rule-based IDS. The model was deployed using IBM Watson Studio, enabling real-time predictions. This system can play a crucial role in strengthening cybersecurity in both enterprise and public networks.
