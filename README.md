# 🧩 Autism Spectrum Disorder (ASD) — End-to-End ML Project

## 📌 Project Overview
This project builds a complete end-to-end Machine Learning pipeline to predict whether an individual has Autism Spectrum Disorder (ASD) using screening data.

The project covers:
- Data loading
- Exploratory Data Analysis (EDA)
- Data preprocessing
- Model building
- Model evaluation
- Feature importance analysis

---

## 📊 Dataset Information
- Dataset: ASD Screening Adults Dataset  
- Problem Type: Binary Classification (ASD: YES / NO)  
- Total Records: 704  
- Total Features: 21  

---

## 🛠️ Tech Stack
- Python  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  
- xgboost  
- imbalanced-learn  

---

## 📂 Project Workflow

### 1. Data Loading
- Loaded dataset using pandas
- Checked basic structure and sample data

### 2. Data Inspection
- Checked missing values
- Reviewed data types
- Analyzed class imbalance

### 3. Exploratory Data Analysis (EDA)
- Distribution of ASD classes
- Age distribution
- Gender analysis
- Jaundice and family history impact
- AQ score analysis
- Correlation heatmap

### 4. Data Preprocessing
- Converted categorical features into numeric
- Handled missing values
- Prepared dataset for modeling

### 5. Model Building
- Logistic Regression  
- Random Forest  
- XGBoost  

### 6. Model Evaluation
- Accuracy score  
- Confusion matrix  
- Precision, Recall, F1-score  
- ROC-AUC score  

### 7. Feature Importance
- Identified key features influencing predictions

---

## 📈 Key Insights
- AQ screening scores are strong predictors  
- Some demographic features show patterns  
- Dataset has class imbalance  
- Ensemble models like XGBoost perform better  

---

## 🚀 How to Run

### 1. Clone Repository
git clone https://github.com/your-username/asd-ml-project.git  
cd asd-ml-project  

### 2. Install Dependencies
pip install -r requirements.txt  

### 3. Run Notebook
jupyter notebook ASD_End_to_End_Project.ipynb  

---

## 📁 Project Structure
ASD_End_to_End_Project.ipynb  
Autism.csv  
README.md  
requirements.txt  

---

## 📌 Future Improvements
- Deploy using Flask or FastAPI  
- Build dashboard using Streamlit or Power BI  
- Perform hyperparameter tuning  
- Use more datasets for better generalization  

---

## 🤝 Contributing
Contributions are welcome. Feel free to fork and submit a pull request.

---

## 📬 Contact
For any queries or suggestions, feel free to connect.

---

## ⭐ Acknowledgements
- Public ASD Screening Dataset  
- Open-source libraries and community  
