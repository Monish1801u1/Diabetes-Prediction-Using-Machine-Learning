# Diabetes Prediction using Machine Learning 🧠💉

This project uses machine learning models like Logistic Regression, SVM, and XGBoost to predict whether a person has diabetes based on health-related input features.

## 🔧 Features
- Real-time predictions using 8 medical inputs
- Data cleaning and preprocessing with StandardScaler
- Handles missing values with median imputation
- Model evaluation using accuracy, recall, and F1-score
- Final model: XGBoost + SMOTE for improved balance

## 📊 Final Model Performance
- Accuracy: **84%**
- Balanced F1-score: **0.85**
- High recall for diabetic cases

## 🚀 How to Run
1. Clone this repository
2. Install required packages: `pip install -r requirements.txt`
3. Run the notebook: `diabetes_prediction.ipynb` or execute `main.py`

## 📁 Files Included
- `main.py`: executable Python script for prediction
- `diabetes_prediction.ipynb`: notebook version of the code
- `diabetes.csv`: dataset used for training and testing
- `report/`: includes documentation (.docx) files
- `README.md`: project overview and instructions

## 📌 Dataset Source
Pima Indian Diabetes Dataset from [Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)

---
Developed as part of a machine learning project for predicting diabetes using real-world data.
