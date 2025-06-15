# 🧠 Privacy-Preserving Deep Learning with Learnable Image Encryption on Medical Images

## 🔐 Overview
This project presents an advanced system that enables secure tumor detection on encrypted medical images using a hybrid of deep learning models and image encryption techniques. The architecture ensures patient privacy while maintaining diagnostic accuracy.

Key Components:
- Learnable image encryption (e.g., Logistic-Sine)
- Classic filters (Median, Mean, Max, Min, Negative, etc.)
- AES encryption for secure transmission
- Tumor classification using pre-trained CNNs: DenseNet-121 & Xception
- Flask-based web interface with access-controlled decryption

---

## 🎯 Objectives
- **Privacy First**: Encrypt images before model inference to ensure patient data confidentiality.
- **Model Accuracy**: Leverage state-of-the-art CNNs for tumor detection.
- **Doctor-Only Decryption**: Secure access control for decryption with password-protected accounts.
- **Explainability Ready**: Future support for SHAP/LIME explainability and federated learning.

---

## 🧪 Features

### 🧬 Tumor Classification
- **DenseNet-121** and **Xception** CNNs classify encrypted images.
- Predicts probability and label: `Tumor` or `No Tumor`.

### 🔐 Encryption Techniques
- **Classical Filters**: Median, Mean, Max, Min
- **Image Inversions**: Negative-Positive, Color Shuffling
- **Learnable Method**: Logistic-Sine Encryption (chaotic system)
- **AES**: Byte-level encryption for secure external transmission

### 🧑‍⚕️ Doctor Access Control
- Predefined authorized doctor credentials.
- Only authenticated users can decrypt and review encrypted images.

---
## 🚀 How to Run the Application

### ✅ Prerequisites
- Python ≥ **3.7** (Recommended: **Python 3.11.0**)
- PIP package installer

### 📦 Installation Steps

1. **Clone the Repository** or Download the ZIP:
   ```bash
     git clone 
   cd your-repo
2. **Install Dependencies**
   pip install -r requirements.txt
3. **Run the Flask Web App**
   python app.py
   
### 📌 Future Work

- 🌍 Integration of federated learning for decentralized training

- 🔍 Incorporation of SHAP/LIME for model interpretability

- 📱 Deployment to cloud or mobile-ready environment

- 🔧 GUI tool for local hospital systems with user-friendly interface



