# Experiment No. 14: Data Normalization and Data Types

**Name:** Ansh Srivastava
**PRN:** 25070123015
**Branch:** F.Y. E&TC (2025–29)  
**Batch:** A1  
**Subject:** Exploratory Data Analysis with Python  

---

## 1. Aim
The aim of this experiment is to study and implement **data normalization techniques** and understand different **data types**, along with converting categorical data into numerical form for effective data analysis.

---

## 2. Objective
- To understand the concept of **data normalization** and its importance.
- To apply different normalization techniques such as **Min-Max, Z-Score, and Decimal Scaling**.
- To understand different **types of data (numerical and categorical)**.
- To convert categorical data into numerical format using encoding techniques.
- To prepare datasets suitable for machine learning and analysis.

---

## 3. Concepts Used

### 3.1 Data Normalization
Data normalization is the process of scaling numerical values into a specific range so that all features contribute equally to analysis.

### 3.2 Types of Normalization
- Min-Max Normalization  
- Z-Score Normalization  
- Decimal Scaling  

### 3.3 Data Types
- Numerical Data (Continuous and Discrete)  
- Categorical Data  

### 3.4 Encoding Techniques
- Label Encoding  
- One-Hot Encoding  
- Dummy Encoding  

---

## 4. Theory

### 4.1 Introduction to Data Normalization

In real-world datasets, values often vary widely in scale. For example, price values may be in thousands, while ratings may be in decimals. Such differences can affect data analysis and machine learning models. Data normalization helps in bringing all values to a common scale without losing their relative differences.

---

### 4.2 Need for Normalization

- Ensures fair comparison between variables  
- Prevents bias due to large values  
- Improves performance of machine learning algorithms  
- Helps in faster convergence during training  

---

### 4.3 Types of Normalization Techniques (With Formulas)

#### 1. Min-Max Normalization

This technique rescales data into a fixed range (usually 0 to 1).

Formula:  
X' = (X - X_min) / (X_max - X_min)
