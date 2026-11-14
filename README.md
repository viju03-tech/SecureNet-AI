# SecureNet AI - Network Intrusion Detection System

A Flask web application that detects network attacks using a CNN-LSTM deep learning model trained on the CIC-IDS2017 dataset.

## Features
- User signup and login
- Dashboard for traffic analysis and attack detection
- CNN-LSTM model for classifying network flows (DDoS, PortScan, Web Attacks, Infiltration, etc.)

## Tech Stack
Python, Flask, TensorFlow/Keras, scikit-learn, SQLite, HTML/CSS/JS

## Setup
1. Clone the repo:
   ```
   git clone https://github.com/viju03-tech/SecureNet-AI.git
   cd SecureNet-AI
   ```
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Download the CIC-IDS2017 CSV files (search "CIC-IDS2017 UNB") and place them in a `dataset/` folder.
4. Run:
   ```
   python app.py
   ```
5. Open http://localhost:5000

## Project Structure
- `app.py` - Flask application
- `models/` - trained model, scaler and label encoder
- `templates/` - HTML pages
- `network-intrusion-detection-cic-ids-dataset.ipynb` - model training notebook

## Dataset
CIC-IDS2017 by the Canadian Institute for Cybersecurity. The files are too large for GitHub, so download them separately.
