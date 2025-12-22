# Laptop Price Prediction using Machine Learning
## Overview
This project implements a machine learning model to predict laptop prices based on various features such as company, type, screen resolution, CPU, RAM, memory, GPU, operating system, weight, and screen size. The notebook includes data preprocessing, exploratory data analysis (EDA),feature engineering and model training using multiple regression algorithms, including 
Linear regression, Lasso regression, Ridge regression, KNN, Decision Tree, SVM, Random Forest, and AdaBoost. The goal is to identify the best-performing model for accurate price prediction.

---

## 🔍 Dataset Description

The dataset contains information about laptops with features such as:

- Company
- Type of Laptop
- Screen Resolution
- Screen Size
- CPU
- RAM
- Memory (HDD / SSD / Hybrid / Flash)
- GPU
- Operating System
- Weight
- Price (Target Variable)

---

## 🌐 Live Demo

🚀 **The project is deployed and accessible here:**  
👉 **https://laptop-price-prediction-using-ml.streamlit.app/**

---

## Project Structure
The notebook is organized into the following sections:

---

## 🧹 Data Preprocessing

- Removed unnecessary columns (e.g., `Unnamed: 0`)
- Converted `RAM` and `Weight` into numeric formats
- Ensured no missing values or duplicate records
- Cleaned and standardized categorical values

---

## 📊 Exploratory Data Analysis (EDA)

- Analyzed price distribution using histograms
- Visualized relationships between price and key features
- Identified trends and outliers affecting pricing
- Gained insights to guide feature engineering

---

## 🔧 Feature Engineering

- Extracted storage components from the `Memory` column:
  - SSD
  - HDD
  - Hybrid
  - Flash Storage
- Transformed categorical variables for model compatibility
- Improved predictive power through engineered features

---

## 🤖 Model Training

The following regression models were trained and evaluated:

- Linear Regression  
- Ridge Regression  
- Lasso Regression  
- K-Nearest Neighbors (KNN)  
- Decision Tree Regressor  
- Support Vector Machine (SVM)  
- Random Forest Regressor  
- AdaBoost Regressor  

All models were implemented using **Scikit-learn Pipelines** with:
- `OneHotEncoder` for categorical variables
- `StandardScaler` for numeric features (where applicable)

---

## 📈 Model Evaluation

- Compared models using standard regression metrics(R2 score, Mean Absolute Error)
- Identified **Random Forest Regressor** as the best-performing model
- Ensured fair comparison through consistent preprocessing

---

## ▶️ How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/LamaNima/Laptop_price_prediction.git
cd Laptop_price_prediction

```

### 2. Create a Virtual Environment
####  Windows 
```bash
python -m venv venv
venv\Scripts\activate
```

#### macOS/Linux
```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Required Libraries
```bash
pip install -r requirements.txt
```

### 4. Run the app 
```bash
streamlit run app.py
```

### 5. Access the local host
```bash
http://localhost:8501/
```



