# 🧩 Autism Spectrum Disorder (ASD) Dataset Overview

## 📌 Project Overview
This project uses a screening dataset to analyze and predict Autism Spectrum Disorder (ASD) in individuals. The dataset contains behavioral, demographic, and screening test attributes that help in identifying ASD traits.

---

## 📊 Dataset Summary

- **Dataset Name:** ASD Screening Adults Dataset  
- **Type:** Tabular Data  
- **Task:** Binary Classification (ASD: YES / NO)  
- **Total Records:** 704  
- **Total Features:** 21  
- **Target Variable:** Class/ASD (indicates whether a person has ASD or not)

---

## 📁 Features Description

### 🧠 Screening Test Features (AQ-10)
These are the main behavioral screening questions:

- A1_Score to A10_Score  
- Binary values (0 or 1)  
- Represent answers to autism-related questions  

---

### 👤 Demographic Features

- **age:** Age of the individual  
- **gender:** Male / Female  
- **ethnicity:** Ethnic background  
- **jundice:** Whether the person had jaundice at birth (Yes/No)  
- **austim:** Family history of autism (Yes/No)  
- **country_of_res:** Country of residence  
- **used_app_before:** Whether the person has used the screening app before  
- **relation:** Who completed the test (self, parent, etc.)  

---

### 📈 Additional Features

- **result:** Final screening score  
- **age_desc:** Age category description  
- **Class/ASD:** Target variable (YES / NO)

---

## ⚠️ Data Characteristics

- Contains both **categorical and numerical features**  
- Includes **binary encoded screening answers**  
- Some features may require **encoding (Label Encoding / One-Hot Encoding)**  
- Dataset may have **class imbalance**  
- Requires preprocessing before model training  

---

## 📊 Potential Use Cases

- ASD prediction using Machine Learning  
- Behavioral pattern analysis  
- Feature importance analysis  
- Healthcare analytics projects  
- Classification model practice  

---

## 🛠️ Data Preprocessing Requirements

- Handle missing values (if any)  
- Encode categorical variables  
- Normalize or scale numerical features  
- Handle class imbalance (if needed)  

---

## 📈 Key Insights (General)

- Screening scores (AQ-10) are highly important  
- Family history and jaundice may influence prediction  
- Demographic features provide additional context  
- Combining behavioral and demographic data improves model performance  

---

## 📂 File Structure
