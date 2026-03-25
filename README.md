# 📊 Student Performance Prediction using Machine Learning

## 🚀 Project Overview
This project predicts the **Performance Index** of students using **Multiple Linear Regression**.  
It demonstrates a complete Machine Learning pipeline including data preprocessing, exploratory data analysis (EDA), model training, evaluation, and validation.

---

## 📁 Dataset
- **File:** `Student_Performance.csv`
- **Source:** Kaggle

### 📌 Features:
- `Hours Studied` → Numeric  
- `Previous Scores` → Numeric  
- `Extracurricular Activities` → Categorical  
- `Sleep Hours` → Numeric  
- `Sample Question Papers Practiced` → Numeric  
- `Performance Index` → Target Variable  

---

## ⚙️ Tech Stack
- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔄 Project Workflow

### 1. Data Loading & Exploration
- Loaded dataset using Pandas
- Checked:
  - Data types (`info()`)
  - Statistical summary (`describe()`)
  - Missing values
  - Duplicate records

---

### 2. Data Preprocessing
- Handled categorical data using **One-Hot Encoding**
- Removed duplicate values
- Split dataset into:
  - Features (X)
  - Target (y)

---

### 3. Exploratory Data Analysis (EDA)
- Correlation heatmap
- Distribution plots
- Analysis of categorical features

---

### 4. Model Building
- Algorithm used: **Multiple Linear Regression**
- Library: Scikit-learn

---

### 5. Train-Test Split
- 80% Training Data  
- 20% Testing Data  

---

### 6. Model Evaluation
- 📈 R² Score  
- 📉 Mean Squared Error (MSE)

---

### 7. Cross Validation
- Applied **5-Fold Cross Validation**
- Ensured model stability and reliability

---

### 8. Visualization
- Scatter plot of:
  - Actual vs Predicted values

---

## 📊 Results
- Model shows strong predictive performance
- Good correlation between study-related features and performance
- Stable results across cross-validation

---

## 🛠️ How to Run

### 1. Clone Repository
```bash
git clone https://github.com/your-username/student-performance-mlr.git
```
cd student-performance-mlr

2. Install Dependencies
pip install pandas numpy matplotlib seaborn scikit-learn
3. Run Notebook
jupyter notebook Student_Performance.ipynb
📂 Project Structure
student-performance-mlr/
│── Student_Performance.ipynb
│── Student_Performance.csv
│── README.md
│── requirements.txt
🔮 Future Improvements
Try advanced models:
Random Forest
XGBoost
Hyperparameter tuning
Feature engineering
Deploy using Streamlit / Flask
