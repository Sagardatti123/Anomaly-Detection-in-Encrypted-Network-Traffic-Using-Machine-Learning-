# Anomaly-Detection-in-Encrypted-Network-Traffic-Using-Machine-Learning-
Developed a Hybrid Intrusion Detection System using Autoencoder and Isolation Forest to detect anomalies in encrypted network traffic without decryption. Built with Python, TensorFlow, Scikit-learn, and Flask for secure, privacy-preserving, real-time threat detection.

<h1 align="center">
🔐 Anomaly Detection in Encrypted Network Traffic Using Machine Learning
</h1>

<p align="center">

<b>Hybrid Intrusion Detection System using Deep Learning & Machine Learning</b>

Detecting cyber threats in encrypted network traffic without decrypting packet payloads.

</p>

<p align="center">

<img src="https://img.shields.io/badge/Python-3.10-blue?logo=python">
<img src="https://img.shields.io/badge/Flask-Web%20App-black?logo=flask">
<img src="https://img.shields.io/badge/TensorFlow-Deep%20Learning-orange?logo=tensorflow">
<img src="https://img.shields.io/badge/Scikit--Learn-ML-yellow?logo=scikitlearn">
<img src="https://img.shields.io/badge/Status-Completed-success">

</p>

---

# 📖 Overview

This project presents a **Hybrid Intrusion Detection System (HIDS)** that identifies malicious activities in encrypted network traffic without decrypting packet contents. The system combines an **Autoencoder** for learning normal traffic behavior with an **Isolation Forest** for detecting anomalous network flows. A Flask-based web application provides an interactive interface for uploading datasets, analyzing traffic, and visualizing attack distributions in real time.

---

# ✨ Features

- 🔒 Privacy-preserving intrusion detection
- 🤖 Hybrid Autoencoder + Isolation Forest model
- 📂 CSV dataset upload
- ⚡ Real-time traffic analysis
- 📊 Interactive attack visualization
- 🌐 Flask web application
- 📈 Attack percentage statistics
- 🛡 Detects Brute Force, DoS, CryptoMiner (XMRIGCC), and Unknown Anomalies

---

# 🛠 Tech Stack

| Category | Technology |
|-----------|------------|
| Language | Python |
| Backend | Flask |
| Machine Learning | Scikit-Learn |
| Deep Learning | TensorFlow / Keras |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Chart.js |
| Frontend | HTML, CSS, JavaScript |

---

# 🏗 System Architecture

<p align="center">

<img src=Images/System Architecture.png>

</p>

---

# 📸 Application Preview

## 🔹 Upload Network Traffic Dataset

<p align="center">

<img src=Images/data.png>

</p>

---

## 🔹 Attack Detection Dashboard

<p align="center">

<img src=Images/Analyze Traffic.png>

</p>

---

## 🔹 Traffic Analysis Result

<p align="center">

<img src=Images/output.png>

</p>

---

# ⚙️ Project Workflow

```text
CSV Upload
     │
     ▼
Data Preprocessing
     │
     ▼
Feature Scaling
     │
     ▼
Autoencoder
     │
     ▼
Reconstruction Error
     │
     ▼
Isolation Forest
     │
     ▼
Hybrid Decision
     │
     ▼
Attack Detection
     │
     ▼
Visualization Dashboard
```

---

# 📊 Performance

| Dataset | Accuracy |
|----------|----------:|
| ALLFLOWMETER_HIKARI2022 | **93.66%** |
| CSE-CIC-IDS2018 | **90.51%** |
| UNSW-NB15 | Evaluated |

The hybrid model improves anomaly detection by combining reconstruction-based learning with statistical outlier detection, reducing false positives while maintaining strong detection performance across multiple benchmark datasets.

---

# 📁 Project Structure

```text
Anomaly-Detection/
│
├── app.py
├── models/
├── static/
├── templates/
├── images/
│   ├── upload_page.png
│   ├── detection_dashboard.png
│   ├── output_result.png
│   └── system_architecture.png
├── dataset/
├── requirements.txt
└── README.md
```

---

# 🚀 Installation

```bash
git clone https://github.com/Sagardatti123/Anomaly-Detection.git
```

```bash
cd Anomaly-Detection
```

```bash
pip install -r requirements.txt
```

```bash
python app.py
```

---

# 🔮 Future Enhancements

- Live packet capture
- Real-time monitoring
- Docker deployment
- Cloud deployment
- Explainable AI (XAI)

---

# 👨‍💻 Authors

**D. Sagar**  
**G. Tanuja**  
**B. Chandini**  
**S. Sai Kiran**

**Department of Computer Science & Engineering (Data Science)**  
**MVGR College of Engineering**

---

<p align="center">

⭐ If you found this project useful, consider giving it a star!

</p>
