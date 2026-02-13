# Phishing Detection ML – Browser Extension

A Machine Learning–based phishing detection system implemented as a browser extension.  
This project was developed as a capstone cybersecurity and AI project.

---

## 🚀 Project Overview

Phishing attacks remain one of the most common cyber threats.  
This project detects potentially malicious URLs in real time using:

- URL feature extraction
- Machine learning classification
- Risk scoring logic
- Browser extension integration

The goal was to build a lightweight detection mechanism that operates without relying solely on blacklist databases.

---

## 🧠 Machine Learning Approach

### Feature Engineering

Extracted features include:

- URL length
- Presence of special characters
- Use of IP address instead of domain
- Suspicious keywords
- Number of subdomains
- HTTPS usage
- Redirection patterns

These features were transformed into structured numerical inputs for model training.

---

### Model Training

The classification model was trained using labeled phishing and legitimate URL datasets.

Algorithms evaluated:

- Logistic Regression
- Decision Tree
- Random Forest

Final model selection was based on:

- Accuracy
- Precision
- Recall
- F1 Score

---

## 🛡️ Security Considerations

- No sensitive user data stored
- No external tracking
- Client-side URL inspection
- Lightweight feature computation

---

## 🧩 System Architecture

1. URL captured in browser
2. Feature extraction module processes URL
3. Trained ML model evaluates risk
4. User alerted if phishing likelihood exceeds threshold

---

## 📊 Results

The model achieved high detection accuracy during validation testing and demonstrated strong performance against known phishing patterns.

Detailed evaluation metrics are included in the official capstone report.

---

## 📄 Documentation

Full technical report available in:

# Phishing Detection ML – Browser Extension

A Machine Learning–based phishing detection system implemented as a browser extension.  
This project was developed as a capstone cybersecurity and AI project.

---

## 🚀 Project Overview

Phishing attacks remain one of the most common cyber threats.  
This project detects potentially malicious URLs in real time using:

- URL feature extraction
- Machine learning classification
- Risk scoring logic
- Browser extension integration

The goal was to build a lightweight detection mechanism that operates without relying solely on blacklist databases.

---

## 🧠 Machine Learning Approach

### Feature Engineering

Extracted features include:

- URL length
- Presence of special characters
- Use of IP address instead of domain
- Suspicious keywords
- Number of subdomains
- HTTPS usage
- Redirection patterns

These features were transformed into structured numerical inputs for model training.

---

### Model Training

The classification model was trained using labeled phishing and legitimate URL datasets.

Algorithms evaluated:

- Logistic Regression
- Decision Tree
- Random Forest

Final model selection was based on:

- Accuracy
- Precision
- Recall
- F1 Score

---

## 🛡️ Security Considerations

- No sensitive user data stored
- No external tracking
- Client-side URL inspection
- Lightweight feature computation

---

## 🧩 System Architecture

1. URL captured in browser
2. Feature extraction module processes URL
3. Trained ML model evaluates risk
4. User alerted if phishing likelihood exceeds threshold

---

## 📊 Results

The model achieved high detection accuracy during validation testing and demonstrated strong performance against known phishing patterns.

Detailed evaluation metrics are included in the official capstone report.

---

## 📄 Documentation

Full technical report available in:

/report/Final Capstone Project Report (Phishing Detection Browser Extension).pdf

---

## 🛠️ Tech Stack

- Python
- Scikit-learn
- Pandas
- NumPy
- JavaScript (Browser Extension)
- HTML/CSS

---

## 📌 Future Improvements

- Real-time model updating
- Deep learning experimentation
- Cloud-based API deployment
- Threat intelligence integration

---

## 👨‍💻 Author

Developed as part of a Capstone Cybersecurity Project.
