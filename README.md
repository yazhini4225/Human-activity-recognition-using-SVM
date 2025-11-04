# 🏃 Human Activity Recognition using SVM

This project demonstrates **Human Activity Recognition (HAR)** using the **Support Vector Machine (SVM)** algorithm.  
The model classifies different human physical activities based on sensor data collected from smartphone accelerometers and gyroscopes.

---

## 🚀 Project Overview

The aim of this project is to automatically recognize human activities such as:
- Walking  
- Sitting  
- Standing  
- Lying down  
- Walking upstairs  
- Walking downstairs  

The dataset contains motion sensor signals collected from smartphones worn by participants while performing daily activities.

---

## 📂 Dataset

**Dataset:**  
[UCI Human Activity Recognition Using Smartphones Dataset](https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones)

**Description:**  
- Data collected from accelerometers and gyroscopes of Samsung Galaxy S smartphones.  
- Each record contains **561 features** representing time and frequency domain variables.  
- Labels represent one of **six activities** performed by participants.

---

## 🧠 Machine Learning Workflow

1. **Importing and Understanding the Dataset**
   - Loaded the dataset using Pandas.
   - Checked class distribution and feature dimensions.

2. **Splitting the Dataset**
   - 80% Training set  
   - 20% Testing set

3. **Model Training**
   - Trained a **Support Vector Machine (SVM)** classifier using `sklearn.svm.SVC`.
   - Tried kernels like `linear`, `poly`, and `rbf`.

4. **Model Evaluation**
   - Evaluated accuracy.
   - Compared kernel performance.

---

## 📊 Results

| Kernel | Accuracy  | Observation              |
|--------|-----------|--------------------------|
| Linear | **96.3%** | Fast, stable results     |
| Poly   | 93.07%    | Slightly better accuracy |
| RBF    | 91.78%    | Best performing kernel   |

✅ **Linear kernel** gave the highest classification accuracy of **96.3%**.

---

## 🧩 Technologies Used

- **Python 3**
- **Pandas**
- **scikit-learn**

