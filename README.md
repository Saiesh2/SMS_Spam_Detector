<div align="center">

# 📩 SMS Spam Detector  
### 🚀 Machine Learning | NLP | Streamlit Web App  

🔍 An intelligent SMS/Email Spam Classification system that detects whether a message is **Spam** or **Not Spam** using Machine Learning and Natural Language Processing.

<br/>

![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red?logo=streamlit)
![ML](https://img.shields.io/badge/Machine%20Learning-NLP-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

</div>

---

## 🌟 Project Overview
This project is an **end-to-end SMS Spam Detection application** built using **Python and Machine Learning**.  
It preprocesses raw text messages, transforms them using NLP techniques, and predicts whether a message is spam or legitimate.

The trained ML model is deployed using **Streamlit**, providing a clean and interactive web interface for real-time predictions.

---

## 🖼️ Application Preview

<div align="center">

### 🔹 Not Spam   
"<img width="1906" height="698" alt="image" src="https://github.com/user-attachments/assets/eeccc4d0-e567-434e-8a5f-a83cb4425e9a" />

<br/><br/>

### 🔹 Spam 
<img width="1913" height="743" alt="image" src="https://github.com/user-attachments/assets/5d09cd17-63e5-46bd-9753-8ed2e1e16081" />

</div>


---

## 🧠 Machine Learning Models Used
- ✅ Multinomial Naive Bayes (Best performer)
- Bernoulli Naive Bayes
- Gaussian Naive Bayes  

Model evaluation was done using:
- Accuracy Score
- Precision Score
- Confusion Matrix  

---

## 🛠️ Tech Stack
| Category | Tools |
|--------|------|
| Language | Python |
| ML & NLP | Scikit-learn, NLTK |
| Data Handling | Pandas, NumPy |
| Web App | Streamlit |
| Model Saving | Pickle |
| Version Control | Git & GitHub |

---

## ⚙️ Workflow
1. Data cleaning & preprocessing  
2. Tokenization, stopword removal & stemming  
3. Feature extraction (BoW / TF-IDF)  
4. Model training & comparison  
5. Best model selection  
6. Model serialization  
7. Deployment using Streamlit  

---

## ▶️ How to Run Locally
```bash
pip install -r requirements.txt
streamlit run SMS_Spam.py
