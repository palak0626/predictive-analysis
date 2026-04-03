#  Sampling Techniques on Imbalanced Dataset

##  Project Overview
This project focuses on handling an imbalanced credit card dataset using different sampling techniques and analyzing their effect on machine learning models.

In real-world datasets, one class often has much more data than the other. This can affect model performance. So, in this project, we first balance the dataset and then apply different sampling methods to study their impact.

---

##  Objectives
- To understand the problem of imbalanced datasets  
- To convert an imbalanced dataset into a balanced one  
- To apply different sampling techniques  
- To train multiple machine learning models  
- To compare accuracy across different techniques  

---

##  Dataset
- Dataset used: Credit Card Dataset  
- Source: [GitHub Dataset Link](https://raw.githubusercontent.com/AnjulaMehto/Sampling_Assignment/main/Creditcard_data.csv)

###  Dataset Details
- Total rows: 772  
- Features: 30 + 1 target column  
- Target column: `Class`
  - 0 → Normal transaction  
  - 1 → Fraud transaction  

---

##  Problem Statement
The dataset is highly imbalanced:
- Majority class (Normal) is much larger  
- Minority class (Fraud) is very small  

This causes machine learning models to become biased toward the majority class.

---

##  Steps Performed

### 1. Data Loading
- Loaded dataset using pandas  
- Checked shape and columns  

### 2. Data Visualization
- Used bar chart to show imbalance in class distribution  

### 3. Data Balancing
- Applied Random Undersampling  
- Created a balanced dataset  

### 4. Sampling Techniques Used
After balancing, the following sampling methods were applied:

- Simple Random Sampling  
- Stratified Sampling  
- Systematic Sampling  
- Cluster Sampling  
- Bootstrap Sampling  

Each method generated a different sample dataset.

---

##  Machine Learning Models Used

| Model | Description |
|------|------------|
| Logistic Regression | Simple linear classification model |
| Decision Tree | Uses tree structure for decision making |
| Random Forest | Combination of multiple decision trees |
| KNN | Classifies based on nearest neighbors |
| SVM | Finds best boundary between classes |

---

##  Model Training
- Dataset was split into training and testing sets  
- Data scaling was applied using StandardScaler  
- Models were trained on each sample  
- Accuracy was calculated  

---

##  Results

A comparison table was created for:

**Models vs Sampling Techniques**

<img width="455" height="143" alt="image" src="https://github.com/user-attachments/assets/b8b9036f-6780-4880-bbd0-8f7a48c50cc0" />


---

##  Analysis
- Stratified sampling gave stable and consistent results  
- Bootstrap sampling performed well due to more data variation  
- Cluster sampling showed lower accuracy due to limited data  
- Random Forest performed best among models  

---

##  Conclusion
- Imbalanced datasets can reduce model performance  
- Balancing the dataset improves accuracy  
- Different sampling techniques give different results  
- Choosing the right technique is important  

---

##  Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  
- Imbalanced-learn  

---

