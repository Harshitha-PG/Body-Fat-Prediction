# 🧠 Body Fat Prediction using Machine Learning

This repository contains a machine learning project that predicts body fat percentage based on various physical and demographic features. The project utilizes a range of regression models to evaluate prediction performance.

## 📊 Dataset

The dataset used is from Kaggle:

**🔗 [Body Fat Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/body-fat-prediction-dataset)**  
It includes 252 records with features such as:

- Age
- Weight
- Height
- Body density
- Abdomen circumference
- Wrist, ankle, hip, forearm measurements
- Percent body fat (target variable)

---

## 📁 Project Contents

- `MLProject.ipynb`: Main Jupyter Notebook with the complete workflow — data preprocessing, model training, and evaluation.
- `README.md`: Project overview and instructions.

---

## 📌 Project Workflow

### 1. 🧼 Data Preprocessing
- Handling missing values
- Removing outliers
- Feature selection
- Standardization of features

### 2. 📊 Exploratory Data Analysis (EDA)
- Distribution plots
- Pairplots and correlation heatmaps
- Visual relationship between features and body fat percentage

### 3. 🤖 Model Building
- **Linear Regression**
- **Ridge Regression**
- **Lasso Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**

### 4. 📈 Model Evaluation
Models are evaluated using:
- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

### 5. 🧪 Comparison and Results
Visual comparison of all models to identify the best-performing one based on prediction accuracy and error metrics.

---

## 🛠️ Installation & Requirements

Create a virtual environment and install the required libraries:

```bash
pip install -r requirements.txt

