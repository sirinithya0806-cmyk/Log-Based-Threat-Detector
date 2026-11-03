# Log-Based Threat Detector

## Overview
A Python-based security tool that analyzes SSH authentication logs to detect brute-force attacks and suspicious login behavior using rule-based detection and Isolation Forest.

## Features
- SSH log parsing using Regular Expressions
- Brute-force attack detection
- Password spraying-like activity detection
- Isolation Forest anomaly detection
- MITRE ATT&CK mapping
- Security alerts exported to CSV
- Data visualization

## Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Dataset
Loghub OpenSSH Logs:
https://github.com/logpai/loghub

## Limitations
- Detection thresholds are heuristic.
- The SSH dataset does not contain ground-truth labels.
- ML evaluation uses controlled simulated data.

## Future Improvements
- Streamlit dashboard
- Real-time log monitoring
- Improved anomaly detection
- Evaluation using labeled datasets
