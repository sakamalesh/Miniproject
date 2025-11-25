## 🚀 Crypto Algorithm Detector
A machine-learning powered system that automatically identifies whether a given text is encrypted, hashed, or plaintext — such as AES, RSA, SHA-256, Caesar Cipher, or unencrypted data.

## 📌 Title of the Project
Crypto Algorithm Detector – Machine Learning–Based Cryptographic Classification System

A smart and automated cryptographic identification tool that uses machine learning to classify encrypted, hashed, or plain text. The system helps cybersecurity professionals, forensic analysts, and students quickly determine which cryptographic algorithm was used.

## 📖 About
 The Crypto Algorithm Detector is a full-stack project designed to identify the underlying cryptographic algorithm behind a given text sample.
In cybersecurity and digital forensics, analysts frequently encounter ciphertext or hashed values without any accompanying metadata. Manual identification is slow, error-prone, and requires expert knowledge.
This project eliminates those challenges by integrating:

      Machine Learning (Random Forest Classifier)
      
      Statistical Feature Extraction (Entropy, character frequency, randomness)
      
      Full-stack Web Application (Flask + HTML/CSS/JS)
      
      The detector takes any input text and predicts the algorithm used, helping analysts make quicker decisions and enabling students to practically understand cryptographic outputs.

## ⭐ Features

🔐 Classifies AES, RSA, SHA-256, Caesar Cipher, and Plaintext

🤖 Uses a trained Random Forest Machine Learning model

⚡ Real-time prediction (< 1 second)

📊 Extracts advanced statistical features (entropy, ASCII distribution, randomness score)

🌐 Frontend–Backend integrated full-stack system

📈 High scalability and extendable to more algorithms

🧩 JSON-based structure for easy API integration

🛠️ Lightweight Flask framework for deployment

## 🖥️ Requirements

## Software Requirements

Operating System: Windows 10 / Ubuntu (64-bit recommended)

Programming Language: Python 3.8 or later

Backend Framework: Flask

Machine Learning Libraries:

scikit-learn

NumPy

Pandas

## Additional Libraries:

hashlib

cryptography (for synthetic data generation)

pickle (for model loading)

Frontend: HTML5, CSS3, JavaScript

IDE: VS Code / PyCharm

## Hardware Requirements

Processor: Minimum Intel i3 / AMD equivalent

RAM: 4GB (8GB recommended for model training)

Storage: At least 1GB for datasets and logs

## 🏗️ System Architecture

Below is the architecture workflow of your Crypto Algorithm Detector:

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/79c9868b-85bb-4fff-81cf-0da2313452f8" />


🖼️ Output
Output 1 – ML Prediction Interface

(Insert screenshot here)
Shows the web interface where the user inputs ciphertext and receives the predicted algorithm.

Output 2 – Entropy & Feature Calculation

(Insert screenshot here)
Displays internal feature extraction values such as entropy, frequency distribution, etc.

Detection Accuracy: 92% – 95%
(Customize based on your model’s performance)

## 📊 Results and Impact

The Crypto Algorithm Detector significantly improves the speed and accuracy of identifying encryption methods.
The system:

Enhances cyber-forensic investigations

Helps students learn cryptographic patterns

Supports CTF competitions where fast crypto identification is crucial

Enables automated, reliable, and real-time classification

It also serves as a foundation for building more advanced cybersecurity automation tools.

## 📚 Articles Published / References

Scikit-learn Developers, “Random Forest Classifier Documentation,” 2024.

Shannon, C. E., “Communication Theory of Secrecy Systems,” Bell Labs, 1949.

Flask Official Documentation, Pallets Framework, 2024.

Dwyl Organization, “English Word List Repository,” GitHub, 2023.

Python Cryptography Library Documentation, 2024.
