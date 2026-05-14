# Kickstarter Funding Prediction

**Predictive Analytics Project** | Forecasting whether Kickstarter projects will succeed or fail in reaching their funding goal.

## 📋 Project Overview
This project builds machine learning models to predict the success or failure of Kickstarter crowdfunding campaigns. By analyzing project characteristics, the models help creators and backers better understand the key factors that drive funding success.

## 🎯 Business / Real-World Value
Crowdfunding success is difficult to predict. Accurate models can help project creators make data-driven decisions on goal setting, campaign strategy, and marketing, while helping backers identify promising projects.

## 🗂️ Dataset
- **Source**: Kickstarter projects dataset ([Kaggle](https://www.kaggle.com/datasets/oscarvilla/kickstarter-nlp))
- **Target**: Binary classification (`successful` vs `failed`)
- **Features**: Project goal, pledged amount, duration, category, country, number of backers, sentiment in project description, launch timing, etc.

## 🔧 Key Techniques & Models
- **Data Preprocessing**: Feature engineering (duration, goal in USD, text features), handling missing values, and encoding categorical variables
- **Exploratory Data Analysis**: Analysis of success rates by category, goal size, country, and temporal trends
- **Modeling**:
  - Logistic Regression (baseline)
  - Random Forest
  - Gradient Boosting
  - XGBoost, LightGBM, CatBoost
- **Advanced Techniques**: Hyperparameter tuning, feature importance analysis, and probability threshold optimization

## 📊 Results
- Strong predictive performance using ensemble tree-based models
- Identified the most important predictors of success (e.g., goal amount, number of backers, project category, and campaign duration)
- Achieved good balance of precision and recall for identifying successful campaigns

## 📄 Reports
- [Full Project Report (PDF)](Kickstarter%20Funding%20Prediction/Reports/Kickstarter%20Funding%20Prediction%20Report.pdf)
- [Presentation Slides (PDF)](Kickstarter%20Funding%20Prediction/Reports/Kickstarter%20Funding%20Prediction%20Slides.pdf)

## 🛠️ Technologies Used
**Python** • **pandas** • **scikit-learn** • **XGBoost** • **LightGBM** • **CatBoost** • **Matplotlib** • **Seaborn**
