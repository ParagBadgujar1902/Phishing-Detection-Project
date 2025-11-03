# 🎯 Phishing Detection: Enhancing Security through URL Feature Analysis

**Program:** M.Sc. in Statistics (Specialization in Industrial Statistics)  
**University:** Kavayitri Bahinabai Chaudhari North Maharashtra University, Jalgaon  
**Date:** November 2024  

---

## 👥 Authors
- **Ashvini Ashok Bhadane**  
- **Parag Kishor Badgujar**  
- **Siddhant Sudhakar Patil**

---

## 📖 Project Overview
This project addresses the growing issue of **phishing detection** through **URL feature analysis**, which provides a faster and more efficient approach than traditional content-based methods.  

The study leverages both **statistical methods** and **machine learning (ML)** techniques to classify URLs as **legitimate** or **phishing**.  

The primary goal is to enhance **cybersecurity** by developing a **robust, real-time phishing identification system**.

---

## 🔧 Methodology & Techniques

### 1️⃣ Feature Extraction
Key features were extracted from URLs for analysis, including:

- URL Length and Domain Length  
- Domain and URL Entropy (a measure of randomness)  
- Count of special characters (e.g., `@`, `?`, `=`, digits, and hyphens)  
- Presence of query or fragment components  

---

### 2️⃣ Feature Selection
Statistical techniques were used to identify impactful features and reduce overfitting:

- **Chi-Squared Test:** Used to find significant associations between categorical features (e.g., `has_digits_in_domain`) and the target variable.  
- **Recursive Feature Elimination (RFE):** Employed to systematically select the most important numerical features for model optimization.

---

### 3️⃣ Machine Learning Models
Several ML classifiers were trained and compared to identify the most effective model:

- Logistic Regression  
- Random Forest  
- Gradient Boosting  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)

---

## 📊 Key Results

The performance of all models was evaluated using **Accuracy**, **Precision**, **Recall**, and **F1-Score**.

| Model | Accuracy (%) |
|:------|:--------------|
| **Random Forest** | **85.10** |
| Gradient Boosting | 84.05 |
| Support Vector Machine (SVM) | 83.06 |

✅ **Random Forest** emerged as the top-performing model for phishing URL classification.

---

## 🛠️ Tools & Libraries Used
- **Python**  
- **Pandas** – Data loading and manipulation  
- **Scikit-learn (sklearn)** – ML models (Random Forest, SVM, etc.), feature selection (RFE), and performance metrics  
- **Matplotlib** & **Seaborn** – Data visualization (histograms, boxplots, etc.)

---

## 📁 Author Information
**Parag Badgujar**  
*M.Sc. in Statistics, 2024*  
*KBC NMU, Jalgaon*  

---

