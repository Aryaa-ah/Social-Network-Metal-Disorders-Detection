# 🧠 Social Network Mental Disorders Detection (SNMDD)

> A machine learning-based mental health diagnostic tool built to detect psychological conditions arising from social media overuse.  
> Developed as a **final year engineering project** (2020–2021) at **D.Y. Patil College of Engineering, Kolhapur**.

[![DOI](https://img.shields.io/badge/Published-IJRASET-blue)](https://doi.org/10.22214/ijraset.2023.55901)


---

## 📌 Project Summary

Social media overuse is linked with emerging behavioral disorders like:

- **Cyber-Relationship Addiction**
- **Net Compulsion**
- **Information Overload**

This application uses **supervised machine learning algorithms** (Decision Tree, One-Class SVM, Ensemble Models) and a **Tkinter-based GUI** to predict the type of disorder based on user symptoms.

🧑‍⚕️ Designed to assist individuals, caregivers, and institutions with **early detection of psychological stress patterns** from social network usage.

---

## 🎓 Academic Details

- **Institution**: D. Y. Patil College of Engineering & Technology, Kolhapur  
- **Department**: Computer Science and Engineering  
- **Academic Year**: 2020–2021  
- **Project Type**: Final Year Capstone / Mega Project  
- **Guide**: Mrs. Sonali Shinge  
- **Published in**: IJRASET, Volume 11 Issue IX (Sep 2023)  
- **DOI**: [10.22214/ijraset.2023.55901](https://doi.org/10.22214/ijraset.2023.55901)

---

## 👨‍💻 Project Contributors

| Name                         | 
|------------------------------|
| Siddharth Yogesh Nashikkar   |
| Aryaa Prashant Hanamar       |
| Nuren Imtiyaz Pathan         |
| Heena Mashak Mulla           | 


---

## 🧠 System Overview

| Component        | Description                                                                            |
|------------------|----------------------------------------------------------------------------------------|
| **Frontend**     | Python Tkinter GUI for user interaction                                                |
| **Backend**      | Python-based ML model using `scikit-learn`, `pandas`, `numpy`                          |
| **ML Models**    | Decision Tree Classifier, One-Class SVM, Ensemble of SVMs                              |
| **Prediction**   | Based on 5 symptoms selected by the user from a dropdown list                          |
| **Categories**   | Information Overload (IO), Cyber Relationship (CR), Net Compulsion (NC)                |
| **Accuracy**     | Achieved up to **90% accuracy** using stratified 5-fold cross-validation               |

---

## 🧩 Features

- 🧪 Predicts SNMDs based on 5 symptoms
- 🔍 User-friendly interface using Tkinter
- 📉 Real-time feedback on prediction confidence
- 📊 Model trained on curated datasets from Kaggle
- 🔐 Lightweight and offline compatible

---



## 🛠 Installation & Run

```bash
git clone https://github.com/sid732/Social-Network-Metal-Disorders-Detection.git
cd Social-Network-Metal-Disorders-Detection
pip install -r requirements.txt
python main.py
