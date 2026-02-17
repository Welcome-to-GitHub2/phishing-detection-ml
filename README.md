# Phishing Detection ML – Browser Extension

A Machine Learning–based phishing detection system implemented as a browser extension.  
This project was developed as a Capstone Cybersecurity and Artificial Intelligence project.

---

## 🚀 Project Overview

Phishing attacks remain one of the most prevalent cybersecurity threats, targeting users through deceptive URLs and spoofed domains.

This project detects potentially malicious URLs in real time using:

- URL feature extraction
- Machine learning classification
- Risk scoring logic
- Browser extension integration

The objective was to build a lightweight detection mechanism that does not rely solely on blacklist databases, but instead performs intelligent feature-based analysis.

---

## 🧠 Machine Learning Approach

### Feature Engineering

The following features were extracted from URLs:

- URL length  
- Number of special characters  
- Presence of an IP address instead of a domain  
- Suspicious keywords (e.g., login, verify, update)  
- Number of subdomains  
- HTTPS usage  
- Redirection indicators  

These features were transformed into structured numerical inputs suitable for supervised learning.

---

### Model Training

The classification model was trained using labeled phishing and legitimate URL datasets.

Algorithms evaluated:

- Logistic Regression  
- Decision Tree  
- Random Forest  

Final model selection was based on the following evaluation metrics:

- Accuracy  
- Precision  
- Recall  
- F1 Score  

Cross-validation techniques were applied to reduce overfitting and ensure generalization.

---

## 🛡️ Security Considerations

- No sensitive user data is stored
- No external tracking mechanisms implemented
- Client-side URL inspection
- Lightweight feature computation
- No dependency on third-party blacklist APIs

The system was designed with privacy-first principles.

---

## 🧩 System Architecture

1. URL captured within browser
2. Feature extraction module processes URL
3. Trained ML model evaluates phishing probability
4. Risk score compared against threshold
5. User alerted if phishing likelihood exceeds threshold

---

## 📊 Results

The final model demonstrated strong detection capability during validation testing, achieving high performance across:

- Accuracy
- Precision
- Recall
- F1 Score

Detailed performance metrics and confusion matrix analysis are included in the official capstone report.

---

## 📄 Documentation

Full technical report available in:

```
/report/Final Capstone Project Report (Phishing Detection Browser Extension).pdf
```

---

## 🛠️ Tech Stack

- Python
- Scikit-learn
- Pandas
- NumPy
- JavaScript (Browser Extension)
- HTML
- CSS

---

## 📌 Future Improvements

- Real-time model updating
- Deep learning model comparison
- Cloud-based API deployment
- Threat intelligence feed integration
- WHOIS and domain age feature expansion

---

## 👨‍💻 Author

Developed as part of a Capstone Cybersecurity Project focused on applied machine learning in defensive security systems.
