# house-price-prediction
Built a regression model to estimate house prices using XGBoost. Performed data cleaning, visualization, and model tuning.
# 🏠 House Price Prediction – Advanced Regression with XGBoost

This project involves building a predictive model to estimate house prices using features like lot area, building type, overall quality, and more. The model uses XGBoost for regression and includes preprocessing and evaluation using RMSE and R².

---

## 📑 Table of Contents
- [Objective](#objective)
- [Tools & Technologies](#tools--technologies)
- [Project Workflow](#project-workflow)
- [Model Evaluation](#model-evaluation)
- [Dataset](#dataset)
- [Author](#author)

---

## 🎯 Objective

To predict the sale price of houses based on structural and location-based features. The project demonstrates the end-to-end regression pipeline, from data cleaning to model tuning using XGBoost.

---

## 🧰 Tools & Technologies

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## 🧠 Project Workflow

1. **Data Cleaning**
   - Handled missing values (e.g., lot frontage, garage type)
   - Converted data types appropriately
   - Removed outliers based on price distribution

2. **Exploratory Data Analysis (EDA)**
   - Analyzed sale price trends with respect to quality, year built, lot area, and neighborhood
   - Plotted heatmaps and pairplots to check correlation

3. **Preprocessing**
   - Label encoded categorical features
   - Scaled numerical values
   - Split data into training and test sets

4. **Modeling**
   - Trained XGBoost Regressor on processed features
   - Tuned hyperparameters to reduce overfitting

---

## 📈 Model Evaluation

- **Metric**: Root Mean Squared Error (RMSE), R² Score
- XGBoost outperformed other models with the lowest RMSE and high R²
- Visualized predicted vs actual values using scatter plots

---

## 📂 Dataset Source

[Ames Housing Dataset – Kaggle](https://www.kaggle.com/datasets/prevek18/house-price-prediction)

---

## 👩‍💻 Author

**Sandhya Karri**  
Aspiring Data Scientist | Career Transitioner from Chemistry & Math  
🔗 [LinkedIn](https://www.linkedin.com/in/sandhya-karri-2a3b84212)
