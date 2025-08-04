# Titanic-Survivors
This project analyzes the Titanic dataset to understand survival factors and build a predictive model. 

This project explores the Titanic dataset to predict passenger survival using Logistic Regression. It demonstrates the full data science workflow from data cleaning to model evaluation.

---

## 🔍 Overview

This project investigates which factors most influenced survival on the Titanic and builds a predictive model using Python and Scikit-learn.

---

## 🧠 Key Steps

1. **Data Cleaning**
   - Handled missing values in Age, Embarked, and other columns
   - Created new features like Family_size
   - Encoded categorical variables (e.g., Sex, Embarked)

2. **Exploratory Data Analysis**
   - Visualized survival rates by Sex, Pclass, Fare, and Embarkation point
   - Explored distribution of key variables with Seaborn & Matplotlib

3. **Feature Engineering**
   - Generated dummy variables
   - Engineered meaningful features to improve model performance

4. **Model Training**
   - Used Logistic Regression with Scikit-learn
   - Accuracy on test set: **77.7%**
   - 5-Fold Cross-Validation average accuracy: **~79.5%**

5. **Evaluation**
   - Confusion Matrix
   - Classification Report
   - Feature Importance analysis

---

## 🔑 Key Findings

- **Sex** (female): Strongest predictor of survival
- **Pclass**: 1st class passengers had higher survival odds
- **Fare**: Higher fare increased chance of survival
- **Embarked**: Passengers from Southampton had lower survival odds

---

## 📁 Files

- Titanic.ipynb: Full Jupyter Notebook with code and analysis
- `README.md`: This file

---

## 🧰 Tools & Libraries

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

---

## 📈 Accuracy

- Test Accuracy: **77.7%**
- Cross-Validated Accuracy (5-fold): **~79.5%**

---

## ✅ Conclusion

This project demonstrates the typical machine learning pipeline and shows how basic feature engineering and interpretation can lead to valuable insights using real-world data.

Source: Kaggle datasets
