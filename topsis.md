# title: TOPSIS

## 1. Methodology

The program follows a structured mathematical approach to determine the best alternative among several choices based on multiple criteria:

**Data Pre-processing** 
- The script imports the dataset and isolates numeric criteria from categorical labels

**Vector Normalization** 
- Each element is normalized to a common scale by dividing it by the square root of the sum of squares of each column

**Weighted Normalization** 
- Normalized values are multiplied by user-defined weights to prioritize specific criteria.

**Ideal Solutions Identification**
- ***Ideal Best :*** Maximum value for '+' (benefit) criteria and minimum for '-' (cost) criteria.
- ***Ideal Worst :*** Minimum value for '+' (benefit) criteria and maximum for '-' (cost) criteria.

**Distance Calculation** 
- The Euclidean distance of each alternative from the Ideal Best ($S_i^+$) and Ideal Worst ($S_i^-$) is calculated.

**Performance Score** 
- The final Topsis Score is calculated as $P_i = \frac{S_i^-}{S_i^+ + S_i^-}$.

**Ranking**
- Alternatives are ranked based on the highest performance score.


---

## 2. Description

This project is a command-line Python utility that implements the TOPSIS method for ranking alternatives based on performance across various parameters.

**Core Logic:**
Built using numpy for high-performance math and pandas for data table handling.

**Input Handling:**
Supports both .csv and .xlsx (via conversion).

**Error Management:**
Includes 5+ mandatory checks to ensure the input file is valid and the weight/impact counts are correct.


---

## 3. Output

<img width="791" height="351" alt="image" src="https://github.com/user-attachments/assets/38ebd97f-565f-4309-bc58-003c1f7fdd69" />


---

## 4. Command Line Execution

!python topsis.py data.csv "1,1,1,1,1" "+,+,+,+,-" 102303826-result.csv
