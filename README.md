# 🏥 Medical Insurance Cost Prediction using Machine Learning

## 📌 Project Overview

This project aims to predict **medical insurance charges** based on demographic and health-related attributes using various Machine Learning regression algorithms.

The project follows a complete Machine Learning workflow including:

- Data Exploration (EDA)
- Data Preprocessing
- Feature Engineering using Scikit-learn Pipeline
- Model Training
- Model Comparison
- Hyperparameter Tuning
- Feature Importance Analysis

The objective is to identify the model that provides the most accurate prediction of insurance charges.

---

## 📂 Dataset

- **Source:** Kaggle
- **Dataset:** Medical Cost Personal Dataset
- **Records:** 1338
- **Features:** 6 Input Features + 1 Target Variable

### Features

| Feature | Description |
|----------|-------------|
| Age | Age of the insured person |
| Sex | Gender |
| BMI | Body Mass Index |
| Children | Number of dependent children |
| Smoker | Smoking status |
| Region | Residential region |
| Charges | Medical insurance cost (Target Variable) |

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 🔄 Machine Learning Workflow

1. Import Libraries
2. Load Dataset
3. Exploratory Data Analysis (EDA)
4. Missing & Duplicate Value Check
5. Feature Selection
6. Train-Test Split
7. Data Preprocessing using ColumnTransformer
8. Machine Learning Pipeline
9. Model Training
10. Model Evaluation
11. Hyperparameter Tuning using GridSearchCV
12. Feature Importance Analysis
13. Conclusion

---

## 🤖 Machine Learning Models Used

- Linear Regression
- Ridge Regression
- Lasso Regression
- Decision Tree Regressor
- Random Forest Regressor

---

## 📊 Model Performance

| Model | R² Score |
|--------|---------:|
| Tuned Random Forest | **0.8878** |
| Random Forest | 0.8799 |
| Decision Tree | 0.8194 |
| Linear Regression | 0.8069 |
| Ridge Regression | 0.8060 |
| Lasso Regression | 0.8069 |

---

## 🏆 Best Performing Model

**Tuned Random Forest Regressor**

Performance Metrics:

- **R² Score:** 0.8878
- **MAE:** 2580.77
- **RMSE:** 4540.78

---

## 📈 Feature Importance

The Random Forest model identified the following features as the most influential:

1. Smoking Status
2. BMI
3. Age
4. Number of Children
5. Region
6. Gender

Smoking status was found to be the strongest predictor of medical insurance charges.

---

## 🚀 How to Run

1. Clone the repository.
2. Install the required libraries:

```bash
pip install -r requirements.txt
```

3. Open the notebook:

```bash
jupyter notebook
```

4. Run all cells sequentially.

---

## 📁 Repository Structure

```
Medical-Insurance-Cost-Prediction/
│
├── Medical_Insurance_Cost_Prediction.ipynb
├── insurance.csv
├── requirements.txt
└── README.md
```

---

## 📌 Conclusion

Among all the regression models evaluated, the **Tuned Random Forest Regressor** achieved the highest predictive performance.

The project demonstrates a complete end-to-end Machine Learning workflow using Scikit-learn Pipelines, making it suitable as a portfolio project for data science and machine learning roles.

---

## 👩‍💻 Author

**Alka Singh**

M.Sc. Statistics
