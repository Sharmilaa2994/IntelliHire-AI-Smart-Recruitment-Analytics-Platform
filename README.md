# 🤖 IntelliHire AI Enterprise

### Smart Internship Candidate Screening and Recruitment Analytics Platform

## 📖 About the Project

IntelliHire AI Enterprise is an AI-powered recruitment analytics platform developed to automate and simplify the internship candidate screening process. The application combines Machine Learning, resume analysis and data analytics to help recruiters make faster and data-driven hiring decisions.

The system evaluates candidates based on multiple performance parameters such as CGPA, technical skills, aptitude, communication skills, projects, certifications, GitHub activity and LinkedIn activity.

Instead of manually reviewing every applicant, IntelliHire AI Enterprise intelligently analyzes candidate data and predicts their suitability for recruitment using Machine Learning algorithms.

This project demonstrates the practical implementation of Artificial Intelligence in modern recruitment systems.

---

## 🎯 Project Objectives

* Automate internship candidate screening
* Reduce manual recruitment effort
* Improve hiring accuracy
* Analyze resumes efficiently
* Rank candidates automatically
* Generate intelligent recommendations
* Visualize recruitment analytics
* Maintain historical recruitment records

---

## ✨ Features

### 🔐 Authentication System

* User Registration
* User Login
* Session Management
* Logout Functionality

### 📊 Dashboard

* Total Candidates
* Eligible Candidates
* Industry Ready Candidates
* Average Performance Score

### 🧠 AI Candidate Screening

Candidate evaluation based on:

* CGPA
* Technical Skills
* Aptitude Skills
* Communication Skills
* Projects
* Certifications
* GitHub Activity
* LinkedIn Activity

### 📄 Resume Analyzer

* Upload PDF resumes
* Analyze technical skills
* Generate resume scores
* Extract useful information

### 📈 Analytics Dashboard

* Recruitment insights
* Candidate statistics
* Performance analysis

### 🏆 Candidate Ranking System

* Rank candidates automatically
* Identify top performers

### 📜 History Management

* Store previous candidate evaluations
* Track recruitment records

### 💡 Recommendation Engine

Generate suggestions to improve candidate profiles.

---

## 🏗️ System Workflow

```text
Login/Register
       ↓
Dashboard
       ↓
Candidate Screening
       ↓
Machine Learning Prediction
       ↓
Score Generation
       ↓
Resume Analysis
       ↓
Analytics Dashboard
       ↓
Candidate Ranking
       ↓
History Management
       ↓
Final Recruitment Decision
```

---

## 🛠️ Tech Stack

### Frontend

* HTML5
* CSS3
* Bootstrap
* JavaScript

### Backend

* Python
* Flask

### Database

* SQLite

### Machine Learning

* Scikit-learn

### Python Libraries

* Pandas
* NumPy
* Joblib
* PyPDF
* Werkzeug

### Development Environment

* Visual Studio Code

---

## 🧠 Machine Learning Algorithms Used

### 🌲 Random Forest Classifier

Used to predict candidate suitability based on input parameters.

### 📌 K-Means Clustering

Used to categorize candidates into groups:

* Industry Ready
* Potential Candidate
* Needs Training

---

## 📂 Project Structure

```text
IntelliHire_AI_Enterprise/

app.py
config.py
database.py
requirements.txt

services/
│
├── auth_service.py
├── analytics_service.py
├── ml_service.py
├── resume_service.py
├── report_service.py
└── utils.py

templates/
│
├── login.html
├── register.html
├── dashboard.html
├── screening.html
├── result.html
├── resume.html
├── resume_result.html
├── analytics.html
├── ranking.html
└── history.html

static/
│
├── css/
│   ├── style.css
│   └── dashboard.css
│
└── js/
    └── dashboard.js

models/

dataset/

database/

uploads/
```

---

## 🚀 Installation

### Clone Repository

```bash
git clone <repository-url>
```

### Navigate to Project Folder

```bash
cd IntelliHire_AI_Enterprise
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Create Database

```bash
python database.py
```

### Generate Dataset

```bash
python generate_dataset.py
```

### Train Machine Learning Models

```bash
python train_models.py
```

### Run Application

```bash
python app.py
```

### Open Browser

```text
http://127.0.0.1:5000
```

---

## 🎓 Learning Outcomes

This project helped in understanding:

* Full Stack Web Development
* Flask Framework
* Machine Learning Integration
* Database Management
* Resume Processing
* Data Analytics
* Authentication Systems
* Software Architecture Design

---

## 🔮 Future Enhancements

* Email Notifications
* AI Chatbot Integration
* Interview Scheduling
* Cloud Deployment
* Real-Time Analytics
* Advanced Resume Parsing
* Multi-Role Authentication

---

## ✅ Conclusion

IntelliHire AI Enterprise is a complete AI-powered recruitment management platform developed to modernize internship candidate screening. By integrating Machine Learning, analytics and automation, the system helps organizations make efficient, reliable and intelligent hiring decisions.

This project demonstrates the real-world application of Artificial Intelligence in recruitment and talent acquisition systems.
