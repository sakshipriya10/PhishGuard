# 🛡️ PhishGuard: Phishing Detection System for E-commerce

A machine learning-based project designed to detect phishing websites in real time using smart feature engineering and deep learning models like ANN, CNN, and RNN. Developed as a research project for the 6th semester B.Tech course at NIT Patna.

## 📘 Abstract

Phishing attacks remain one of the most prevalent cybersecurity threats, especially in the e-commerce sector. This project aims to create an intelligent phishing detection system that uses features extracted from URLs and webpage metadata to classify websites as legitimate or phishing. It leverages machine learning and deep learning models, achieving high accuracy without relying on blacklists or third-party APIs.

## 🎯 Objectives

- Build a real-time phishing detection system based on URL and domain features.
- Apply ML/DL models (KNN, ANN, CNN, RNN) for classification.
- Improve detection of zero-day and adversarial phishing attacks.
- Ensure model interpretability and scalability.

## 🧠 Models Implemented

- *K-Nearest Neighbors (KNN)*
- *Artificial Neural Network (ANN)*
- *Convolutional Neural Network (CNN)*
- *Recurrent Neural Network (RNN)*

Each model is evaluated using Accuracy, Precision, Recall, and F1-Score.

## 📊 Dataset Overview

- *Records*: 11,054
- *Features*: 32 (URL structure, domain metadata, HTML behavior, etc.)
- *Labels*: 
  - 1 → Legitimate
  - -1 → Phishing

### Key Features:
- URL length, special characters, domain age, SSL usage
- Google Index presence, redirections, favicon trust
- JavaScript-based obfuscation, right-click disabling, popups

## ⚙️ Preprocessing Techniques

- *SMOTE* for handling class imbalance
- *Variance Threshold* for feature selection
- *Correlation Matrix* to remove redundancy
- *Z-score* and *Min-Max Scaling* for normalization

## 🏁 Results Summary

| Model | Accuracy | Precision | Recall | F1-Score |
|-------|----------|-----------|--------|----------|
| KNN   | 95.4%    | 95.2%     | 95.3%  | 95.2%    |
| ANN   | 96.2%    | 96.6%     | 95.7%  | 96.1%    |
| CNN   | 99.0%    | ~         | ~      | ~        |
| RNN   | ~96.0%   | ~96.1%    | ~95.9% | ~96.0%   |

> 📌 ANN showed best practical performance. CNN reached highest test accuracy with perfect tuning.

## 🚀 Deployment Possibilities

- Browser extensions for real-time phishing alerts
- Proxy filters for enterprise security
- Mobile integrations for e-commerce protection

## 🔮 Future Enhancements

- Real-time browser extension deployment
- Online learning for adapting to new phishing techniques
- Use of federated learning for privacy-preserving training
- Multimodal phishing detection using webpage screenshots
- Integration with keystroke patterns and session behaviors

## 👩‍💻 Contributors

- Isha - 2247026  
- Sakshi Priya - 2206274  
- Nikita Kumawat - 2247027  

Under the guidance of  
*Dr. Kakali Chatterjee*, Associate Professor  
Department of Computer Science & Engineering  
National Institute of Technology Patna
