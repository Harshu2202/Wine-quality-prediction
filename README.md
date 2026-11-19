# 🍷 Wine Quality Prediction Using Machine Learning

## 📌 Project Overview

This project aims to predict the quality of red wine using its physicochemical properties through Machine Learning regression techniques.

The objective is to understand how different chemical characteristics influence wine quality and develop models that estimate wine quality score.

##  📊 Dataset

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

1. **Data Collection** – Gather the Wine Quality dataset containing physicochemical properties and quality ratings.
2. **Data Loading and Inspection** – Load the dataset using Pandas and inspect shape, data types, and summary statistics.
3. **Data Cleaning and Duplicate Handling** – Check for missing values and remove duplicate entries to ensure data integrity.
4. **Exploratory Data Analysis (EDA)** – Visualize feature distributions and target variable patterns using Matplotlib and Seaborn.
5. **Feature Analysis** – Evaluate feature correlations with wine quality to identify key predictors.
6. **Data Preprocessing** – Prepare input features (`X`) and target labels (`y`), applying scaling or encoding where appropriate.
7. **Train-Test Split** – Partition the dataset into training and testing subsets to evaluate generalization.
8. **Regression Model Development** – Train multiple regression models on the training set.
9. **Model Evaluation** – Assess model performance on unseen test data using standard regression metrics.
10. **Model Comparison** – Compare error rates and variance explained across models to select the best performer.
11. **Cross-Validation** – Apply k-fold cross-validation to verify model stability and prevent overfitting.
12. **New Sample Prediction** – Test the trained model on new wine physicochemical inputs to predict quality scores.
13. **Model Saving and Loading** – Serialize the best-performing model with Joblib for future reuse and deployment.

## 🤖 Machine Learning Algorithms

Three regression algorithms were implemented:

- **Linear Regression** – Baseline parametric model assuming a linear relationship between physicochemical features and wine quality.
- **Decision Tree Regressor** – Non-linear tree-based model that splits features based on variance reduction.
- **Random Forest Regressor** – Ensemble bagging method combining multiple decision trees to improve accuracy and reduce overfitting.

## 📈 Model Evaluation Metrics

The models were evaluated using:

- **Mean Absolute Error (MAE)** – Measures the average magnitude of absolute prediction errors.
- **Mean Squared Error (MSE)** – Penalizes larger prediction errors by squaring the residuals.
- **Root Mean Squared Error (RMSE)** – Expresses the square root of MSE in the same units as the wine quality score.
- **R-squared ($R^2$ Score)** – Indicates the proportion of variance in wine quality explained by the model.
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
