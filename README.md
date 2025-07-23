# Employee_Salaryprediction
# 💼 Income Prediction Using Machine Learning

This project predicts whether an individual's income exceeds $50K/year based on census data using various machine learning models. It compares model performance and selects the best-performing one for final deployment.

## 📁 Dataset

- **Source:** UCI Machine Learning Repository  
- **File Used:** `adult 3.csv`  
- **Attributes:** Age, workclass, education, marital status, occupation, relationship, race, gender, hours-per-week, capital-gain/loss, native-country, income

## 🚀 Features

- Cleans and preprocesses raw data
- One-hot encodes categorical variables
- Trains multiple ML models:
  - Logistic Regression
  - Random Forest
  - XGBoost
  - Support Vector Machine (SVM)
- Compares model performance using accuracy and visualization
- Identifies and uses the best model for predictions
- Custom input support for real-time income prediction

## 🧠 Machine Learning Pipeline

1. **Data Preprocessing**
   - Replaces missing values (`?`) with "Other"
   - Drops duplicate entries
   - Applies one-hot encoding

2. **Train-Test Split**
   - 80% training, 20% testing

3. **Model Training & Evaluation**
   - Accuracy score
   - Comparison bar chart
   - Model selection

4. **Prediction Module**
   - Predicts income category from custom inputs

## 📊 Model Performance

| Model               | Accuracy |
|--------------------|----------|
| Logistic Regression| ~84.2%   |
| Random Forest      | ~86.7%   |
| XGBoost            | ~87.1% ✅ |
| SVM                | ~85.5%   |

✅ **Best Model:** XGBoost

## 🖼️ Visualization

  <img width="1013" height="623" alt="Screenshot 2025-07-23 225557" src="https://github.com/user-attachments/assets/cf6fd2ba-a165-48f2-af11-6a5869848620" />

*Comparative bar chart of model performance.*

## 📦 Requirements

```bash
pip install pandas numpy scikit-learn matplotlib seaborn xgboost
```

## 📚 References
- UCI Adult Dataset

- scikit-learn documentation

- XGBoost documentation

🌐 Author :Madhukumar Kareti

📫 Connect on LinkedIn :  [www.linkedin.com/in/madhukumar-kareti-b59155275](https://www.linkedin.com/in/madhukumar-kareti-b59155275/)







