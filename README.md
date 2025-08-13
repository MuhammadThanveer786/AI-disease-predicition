# 🩺 AI Disease Prediction

An AI-powered web application built with **Flask** and **Machine Learning** to predict possible diseases based on user-reported symptoms.  
This project also provides additional health-related resources such as diet plans, disease information, and treatment recommendations.

---

## 🚀 Features
- **Disease Prediction** using trained ML models.
- **Interactive Web Interface** built with Flask, HTML, CSS, and JavaScript.
- **Symptom Severity Analysis** from dataset.
- **Diet Recommendations** for predicted diseases.
- **Contact & Blog Pages** for health awareness.
- **Responsive UI** with Bootstrap.

---

## 📂 Project Structure

```medicine-recommendation/
├── Datasets/
│ ├── Symptom-severity.csv
│ ├── symtoms_df.csv
├── static/
│ ├── css/
│ ├── js/
│ ├── img/
│ ├── vendor/
├── templates/
│ ├── index.html
│ ├── about.html
│ ├── contact.html
│ ├── login.html
│ ├── signup.html
│ ├── home.html
│ ├── symptom_list.html
├── main.py
├── requirements.txt
└── .gitignore
```
## 📊 Dataset Details
This project uses multiple CSV datasets for prediction and recommendation:
- **Symptom-severity.csv** → Severity score for each symptom.
- **symtoms_df.csv** → List of all symptoms mapped to diseases.
- **description.csv** → Detailed information about diseases.
- **diets.csv** → Recommended diets for different diseases.
- **medications.csv** → Suggested medicines and dosages.
- **precautions_df.csv** → Preventive measures for diseases.
- **workout_df.csv** → Exercises for managing diseases.

---

## 🤖 Machine Learning Models
The system is powered by multiple ML algorithms:
- **Support Vector Classifier (SVC)**
- **Random Forest Classifier**
- **K-Nearest Neighbors**
- **Gradient Boosting**
- **Multinomial Naive Bayes**

📌 Models are trained on curated symptom–disease datasets and saved as `.pkl` files for fast prediction.





