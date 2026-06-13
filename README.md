# Multiple-Lenier-Regression
Contains two ML projects: (1) Linear Regression on 50_Startups dataset to predict profit. (2) Multiple Linear Regression on Student Performance dataset with EDA, scatterplot visualizations, feature encoding, train-test split, R² evaluation, and Pickle model deployment.
Here’s a clean and professional **README.md** draft for your repository. It’s structured, concise, and recruiter-friendly:


# Machine Learning Regression Projects

This repository contains two regression-based machine learning projects:

## 1. 50_Startups Dataset
- **Model:** Linear Regression  
- **Target Variable:** Profit  
- **Workflow:**  
  - Data preprocessing  
  - Model training  
  - Performance evaluation using R² score  

## 2. Student Performance Dataset
- **Model:** Multiple Linear Regression  
- **Target Variable:** Performance Index  
- **Workflow:**  
  - Exploratory Data Analysis (EDA)  
  - Feature encoding  
  - Scatterplot visualizations (Previous Score vs Performance Index, Sleep Hours vs Performance Index, Sample Papers vs Performance Index)  
  - Train-test split  
  - Model training and evaluation with R² score  
  - Model saving using **Pickle**  
  - Deployment for predictions  

## 📂 Project Structure
```
├── 50_Startups/
│   └── linear_regression_model.py
├── Student_Performance/
│   └── multiple_linear_regression.py
├── README.md
└── requirements.txt
```
## 🚀 Usage
Run the scripts to train and evaluate models:
```bash
python 50_Startups/linear_regression_model.py
python Student_Performance/multiple_linear_regression.py


## 📊 Results
- **50_Startups:** Predicted company profit using linear regression.  
- **Student Performance:** Predicted performance index with multiple regression, achieving accuracy measured by R² score.  

## 🛠️ Deployment
The student performance model is saved with **Pickle** and can be loaded for deployment:
```python
import pickle
model = pickle.load(open('student_model.pkl', 'rb'))
prediction = model.predict([[...]])
```

---
Build by me 
Learning Data Science & AI/ML 🚀
```


