#  Simulation-Based Machine Learning Model Comparison

---

##  Project Overview

This project focuses on generating synthetic data using simulation techniques and applying multiple machine learning models to compare their performance.

We used Cantera for chemical simulation and Python for data generation and machine learning.

---

##  Objective

- To generate data using simulation  
- To apply multiple machine learning models  
- To compare model performance  
- To identify the best model based on accuracy  

---

##  Simulation Tool Used

- Cantera – used for simulating combustion reactions  
- NumPy – used for generating random data  
- Pandas – used for dataset creation  

---

##  Parameters Used

| Parameter     | Description                          | Range |
|--------------|--------------------------------------|-------|
| Temperature  | Initial temperature of gas           | 900 – 1500 K |
| Pressure     | Initial pressure                     | 1 – 5 atm |
| Time         | Reaction time                        | ~0.001 sec |
| Age          | Random feature (for ML model)        | 18 – 60 |
| Experience   | Random feature (for ML model)        | 0 – 20 |

---

##  Methodology

1. Generated random temperature and pressure values  
2. Used Cantera to simulate gas reaction  
3. Collected output values (temperature, pressure, time)  
4. Created a dataset of 1000 samples  
5. Defined a target variable based on conditions  
6. Split dataset into training and testing sets  
7. Trained multiple machine learning models  
8. Compared model accuracy  

---

##  Machine Learning Models Used

- Logistic Regression  
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  

---

##  Results

| Model                | Accuracy |
|---------------------|----------|
| Logistic Regression | 0.775 |
| Decision Tree       | 1.000 |
| Random Forest       | 1.000 |
| SVM                 |0.610 |
| KNN                 | 0.725 |



---

##  Visualization

A bar graph is used to compare the performance of different models based on accuracy.
<img width="702" height="640" alt="image" src="https://github.com/user-attachments/assets/421b284e-7f4a-4c1c-9e9e-4094662abcbf" />


---

##  Best Model

The model with the highest accuracy is selected as the best performing model.
<img width="279" height="98" alt="image" src="https://github.com/user-attachments/assets/1fa9e3ee-a4e6-464e-a81e-40fde3bbaa77" />


---

