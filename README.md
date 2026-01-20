# Title: Probability Density Function (PDF) 

## 1. Methodology

The following steps were followed to complete this assignment:

**Step 1: Data Collection**
The dataset was loaded from a CSV file using pandas.

**Step 2: Data Cleaning**
- Removed missing(Nan) values
- Removed invalid and negative values
- Converted columns to numeric format

**Step 3: Data Preprocessing**
-Removed extreme outliers using percentile method

**Step 4: Probability Density Function**
-PDF was calculated using cleaned Data
-Distribution of data was analyzed

**Step 5: Result Analysis**
-Mean and other statistics were calculated
-PDF graph was plotted using Matplotlib

---
## 2. Description
- **Dataset Type:** Air Pollution Dataset  
- **Columns Used:** NO2  
- **Total Records:** After cleaning, valid records were used  
- **Missing Values:** Removed  
- **Outliers:** Top 1% removed  
- **Transformation:** Logarithmic  
- **Goal:** To understand data distribution using PDF  

---
## 3. Result Table

| Parameter | Value |
|---------|-------|
| Mean | 24.821444190873866 |
| Variance | 228.81631554695954 |
| lambda | 0.0021851588633651693 |
| c(np.sqrt(lam/np.pi)) | 0.026373427329250715 |

---
## 4. Result Graph

The following graph represents the Probability Density Function (PDF) of the dataset.


<img width="730" height="492" alt="image" src="https://github.com/user-attachments/assets/29b2294a-b2ad-41bb-a078-caefb2a3acfb" />

---

## 5. Conclusion

The Probability Density Function helped in understanding the distribution of air pollution data.  
Data cleaning and preprocessing significantly improved the accuracy of analysis.


