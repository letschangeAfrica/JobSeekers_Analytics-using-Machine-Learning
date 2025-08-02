# JobSeekers Analytics using Machine Learning

![Project Banner](images/img1.PNG)

A machine learning project to streamline recruitment processes by predicting application approval status based on candidate profiles.

## 📌 Project Overview

This project leverages the **JobSeekers_Analytics** dataset to build a classification model that:
- Predicts whether a job applicant's profile will be approved
- Identifies key factors influencing hiring decisions
- Reduces manual screening efforts by up to 40%

Built using the **CRISP-ML(Q)** methodology for maximum transparency and reproducibility.

## 🎯 Business Objectives

**Problem:**  
Hiring managers are overwhelmed with hundreds of applications while quality candidates get missed in manual screening.

![Project Banner](images/img2.PNG)

**Solution:**  
An ML model that:
- Achieves ≥85% accuracy in predicting application status
- Reduces screening costs by 20%
- Provides explainable decisions for HR teams

![Project Banner](images/img3.PNG)

## 📊 Dataset

**JobSeekers_Analytics Dataset (30 features):**
- 1,155 applicant records
- 7 categories of features:
  - Demographics
  - Education & Skills
  - Professional Background
  - Job Preferences
  - Application Metrics
  - Social Presence
  - Target: `Application_Status` (Approved/Rejected/Pending)

## 🛠️ Technical Implementation

**Methodology:** CRISP-ML(Q)  
**Problem Type:** Classification  
**Key Techniques:**
- Data preprocessing
- Feature engineering
- Model evaluation
- Explainable AI

![Project Banner](images/img4.PNG)

**Tech Stack:**
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebooks

## 📂 Repository Structure

/project-root
│── /data
│ └── JobSeekers_Analytics.csv # Raw dataset
│── /notebooks
│ └── JobSeekers_Analytics.ipynb # Main analysis notebook
│── /docs
│ └── ProgressLog.md # Development timeline
│── README.md # Project overview
└── requirements.txt # Dependencies
