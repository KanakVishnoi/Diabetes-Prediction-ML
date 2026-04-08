# 🩺 Diabetes Prediction using Machine Learning

## 📌 Project Overview
This is a beginner-friendly Machine Learning project that predicts whether a person is diabetic or not based on medical attributes.

The project covers:
- Data Analysis
- Data Visualization
- Model Training
- Prediction

---

## ❓ Problem Statement
The goal of this project is to:
👉 Predict whether a person has diabetes using health-related features.

Example Input:
[7,145,66,30,25,32.6,0.351,33]

Output:
👉 0 (Not Diabetic) or 1 (Diabetic)

---

## 📁 Dataset Information

The dataset contains the following features:

- Pregnancies → Number of times pregnant  
- Glucose → Glucose level  
- BloodPressure → Blood pressure value  
- SkinThickness → Skin thickness  
- Insulin → Insulin level  
- BMI → Body Mass Index  
- DiabetesPedigreeFunction → Genetic influence  
- Age → Age of the person  
- Outcome → Target (0 = No Diabetes, 1 = Diabetes)

---

## 🔍 Steps Performed

### 1. Data Loading
- Dataset loaded using pandas

### 2. Data Cleaning
- Checked missing values
- Handled incorrect values

### 3. Data Visualization 📊

#### 🔹 Scatter Plot
- Used to analyze relationship between Age and Outcome  
- Helps understand how diabetes varies with age  

#### 🔹 Histogram
- Shows distribution of Glucose levels  
- Helps identify common ranges and outliers  

#### 🔹 Correlation Heatmap
- Shows relationship between all features  
- Helps in selecting important features  

#### 🔹 Count Plot
- Shows number of diabetic vs non-diabetic cases  
- Helps check data balance  

#### 🔹 Box Plot
- Used to detect outliers in features like BMI  

---

## 🤖 Model Building

- Used Machine Learning algorithm (Logistic Regression)
- Data split into training and testing sets

```python
from sklearn.model_selection import train_test_split

📊 Model Evaluation
Accuracy Score used to evaluate model performance

💡 Important Notes
Always check for missing values before training
Data visualization helps understand patterns
Feature selection improves model accuracy
Avoid overfitting
Use proper train-test split

"Author"
Kanak Vishnoi







