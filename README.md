# 📊 Student Performance Prediction using Multiple Linear Regression

![Python](https://img.shields.io/badge/Python-3.10-blue?style=flat&logo=python)
![Scikit-Learn](https://img.shields.io/badge/ML-Scikit--Learn-orange?style=flat&logo=scikit-learn)
![Status](https://img.shields.io/badge/Project-Completed-success)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 🚀 Overview
This project builds a **Multiple Linear Regression model** to predict students' **Performance Index** based on academic and lifestyle factors.

It demonstrates an **end-to-end Machine Learning workflow** including:
- Data preprocessing  
- Exploratory Data Analysis (EDA)  
- Model training  
- Evaluation & validation  

---

## 📁 Dataset

- **Source:** Kaggle  
- **File:** `Student_Performance.csv`

### 🔢 Features:
| Feature | Type | Description |
|--------|------|------------|
| Hours Studied | Numeric | Study time per day |
| Previous Scores | Numeric | Past academic performance |
| Extracurricular Activities | Categorical | Participation (Yes/No) |
| Sleep Hours | Numeric | Daily sleep duration |
| Sample Question Papers Practiced | Numeric | Practice count |
| Performance Index | Numeric | Target variable |

---

## ⚙️ Tech Stack

- **Language:** Python 🐍  
- **Libraries:**
  - Pandas  
  - NumPy  
  - Matplotlib  
  - Seaborn  
  - Scikit-learn  

---

## 🔄 Workflow

### 📌 1. Data Preprocessing
- Checked missing values & duplicates  
- Encoded categorical feature using **One-Hot Encoding**

---

### 📊 2. Exploratory Data Analysis
- Correlation heatmap  
- Feature distribution plots  
- Relationship analysis between variables  

---

### 🤖 3. Model Training
- Algorithm: **Multiple Linear Regression**
- Train-Test Split: **80 / 20**

---

### 📈 4. Model Evaluation
- **R² Score**
- **Mean Squared Error (MSE)**

---

### 🔁 5. Cross Validation
- Applied **5-Fold Cross Validation**
- Ensured model stability and generalization  

---

### 📉 6. Visualization
- Actual vs Predicted scatter plot  
- Performance comparison  

---

## 📊 Results

- ✅ Strong correlation between study patterns and performance  
- ✅ High R² score indicating good prediction accuracy  
- ✅ Stable results across cross-validation  

---

## 📂 Project Structure
student-performance-mlr/
│── Student_Performance.ipynb
│── Student_Performance.csv
│── README.md
│── requirements.txt


---

## 🛠️ Installation & Usage

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/devendrakushwah80/multiple-linear-regression-student.git
cd multiple-linear-regression-student
2️⃣ Install Dependencies
pip install -r requirements.txt
3️⃣ Run the Notebook
jupyter notebook Student_Performance.ipynb
🔮 Future Enhancements
🚀 Implement advanced models (Random Forest, XGBoost)
🎯 Hyperparameter tuning
📊 Feature engineering
🌐 Deploy using Streamlit or Flask
