# 🏠 House Price Prediction & Feature Analysis (King County, USA)

## 📌 Project Overview
This project analyzes housing data from King County, USA, to identify the key factors influencing house prices and build predictive models using machine learning techniques.

The goal is to support data-driven real estate investment decisions by understanding price drivers and developing reliable prediction models.

---

## 📊 Dataset
The dataset contains housing sales data (2014–2015), including features such as:
- Living area (sqft_living)
- Number of bedrooms and bathrooms
- Location (latitude, longitude)
- House grade and condition
- Waterfront and view indicators

---

## 🔍 Key Steps

### Data Cleaning
- Removed irrelevant columns (id, unnamed)
- Handled missing values using mean imputation

### Exploratory Data Analysis (EDA)
- Correlation analysis to identify key predictors
- Heatmap visualization of feature relationships
- Distribution analysis of house prices
- Boxplots and scatterplots for feature insights

### Feature Insights
Key variables influencing price:
- sqft_living (strongest predictor)
- grade (house quality)
- sqft_above
- bathrooms

### Modeling
- Linear Regression (baseline)
- Multiple Linear Regression
- Ridge Regression (regularization)
- Polynomial Features (interaction modeling)

### Machine Learning Pipeline
Implemented a full pipeline including:
- Missing value imputation
- Feature scaling
- Polynomial feature expansion
- Ridge regression

### Model Evaluation
- R² score for performance evaluation
- Train-test split validation
- Residual analysis

---

## 📈 Key Findings
- Living area is the most important predictor of house prices
- Higher-grade houses are significantly more expensive
- Price distribution is highly skewed → improved using log transformation
- Regularized models (Ridge) improve generalization performance

---

## 🧠 Tools & Technologies
- Python (Pandas, NumPy)
- Data Visualization (Matplotlib, Seaborn)
- Machine Learning (Scikit-learn)
- Google Colab

---

## 🚀 Conclusion
This project demonstrates how data analysis and machine learning can be applied to real estate pricing. The results show that combining multiple features significantly improves predictive performance compared to single-variable models.

---

## 📌 Future Improvements
- Hyperparameter tuning (GridSearchCV)
- Feature selection techniques
- Deploy model as a web app (Streamlit)
- Add geospatial visualization
