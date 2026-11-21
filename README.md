# &#x20;Heart Disease Prediction Using Machine Learning

## 📌 Project Overview

Heart Disease Prediction is a Machine Learning project developed using Python to predict the presence of heart disease based on patient medical attributes.

The project uses different classification algorithms and compares their performance to identify the best-performing model.

## 🎯 Project Objectives

- To analyze heart disease-related medical data.
- To preprocess and clean the dataset.
- To build machine learning classification models.
- To compare model performance using evaluation metrics.
- To optimize the Random Forest model using GridSearchCV.

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

## 📊 Dataset

**Cleveland Heart Disease Dataset**

The dataset contains 14 attributes, including:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Maximum Heart Rate
- Exercise-Induced Angina
- Oldpeak
- Other medical attributes

The target variable is converted into two classes:

- 0 – No Disease
- 1 – Disease Present

## 🤖 Machine Learning Algorithms

Three models are implemented and evaluated:

1. Decision Tree Classifier
2. Random Forest Classifier
3. Optimized Random Forest Classifier

## ⚙️ Methodology

1. Dataset loading and exploration.
2. Data cleaning and missing value handling.
3. Exploratory Data Analysis (EDA).
4. Feature and target separation.
5. Training and testing split (80:20).
6. Model training and prediction.
7. Model evaluation and comparison.
8. Random Forest optimization using GridSearchCV with 5-fold cross-validation.
9. Confusion matrix and classification report generation.

## 📈 Model Performance

| Model                   |   Accuracy |  Precision |     Recall |   F1-Score |
| ----------------------- | ---------: | ---------: | ---------: | ---------: |
| Decision Tree           |     73.77% |     67.65% |     82.14% |     74.19% |
| Random Forest           |     88.52% |     83.87% |     92.86% |     88.14% |
| Optimized Random Forest | **90.16%** | **86.67%** | **92.86%** | **89.66%** |

### 🏆 Best Performing Model

The Optimized Random Forest achieved the highest accuracy of **90.16%** among the three models.

## 📉 Visualizations

- Target Class Distribution
- Feature Correlation Heatmap
- Model Performance Comparison
- Confusion Matrix

## 🚀 How to Run the Project

1. Clone or download this repository.
2. Open the `.ipynb` notebook using Google Colab.
3. Upload the `processed.cleveland.data` dataset when prompted.
4. Run all notebook cells.
5. View the model evaluation results and performance comparison.

## 📁 Project Files

- `Heart_Disease_Prediction.ipynb` – Main project notebook.
- `heart_disease_model_results.csv` – Model performance comparison.

## ⚠️ Disclaimer

This project is developed for educational and academic purposes only. It is not intended to replace professional medical advice, diagnosis, or treatment.

## 👩‍💻 Author

**Aisha Mehrin**

MCA Student | Machine Learning Project
