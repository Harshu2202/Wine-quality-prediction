# 🍷 Wine Quality Prediction Using Machine Learning

## 📌 Project Overview

This project aims to predict the quality of red wine using its physicochemical properties through Machine Learning regression techniques.

The objective is to understand how different chemical characteristics influence wine quality and develop models that estimate wine quality score.

## 📊 Dataset

- **Dataset:** Wine Quality (Red Wine)
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/186/wine+quality)
- **Records:** 1,599
- **Features:** 11 independent variables
- **Target Variable:** Quality

### Features

1. Fixed Acidity
2. Volatile Acidity
3. Citric Acid
4. Residual Sugar
5. Chlorides
6. Free Sulfur Dioxide
7. Total Sulfur Dioxide
8. Density
9. pH
10. Sulphates
11. Alcohol

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Google Colab

## 🔍 Project Workflow

1. Data Collection
2. Data Loading and Inspection
3. Data Cleaning and Duplicate Handling
4. Exploratory Data Analysis (EDA)
5. Feature Analysis
6. Data Preprocessing
7. Train-Test Split
8. Regression Model Development
9. Model Evaluation
10. Model Comparison
11. Cross-Validation
12. New Sample Prediction
13. Model Saving and Loading

## 🤖 Machine Learning Algorithms

Three regression algorithms were implemented:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

## 📈 Model Evaluation Metrics

The models were evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

Additional evaluation included 5-Fold Cross-Validation and Feature Importance Analysis.

## 📂 Project Structure

```text
wine-quality-prediction/
│
├── wine_quality_prediction.ipynb
├── wine_quality_model.pkl
├── wine_features.pkl
├── README.md
├── requirements.txt
└── .gitignore
```

## 🚀 How to Run

1. Clone this repository:

   `git clone https://github.com/Harshu2202/Wine-quality-prediction.git`

2. Install the required libraries:

   `pip install -r requirements.txt`

3. Open the notebook using Google Colab or Jupyter Notebook.

4. Execute the notebook cells sequentially.

5. Use the saved Random Forest model for new wine quality predictions.

## 📌 Project Status

**Completed:** Model development, evaluation, comparison, cross-validation, and prediction testing.

## 👨‍💻 Author

**Harshu**

GitHub: [Harshu2202](https://github.com/Harshu2202)

---

Built as a Machine Learning regression project for practical learning and portfolio development.
