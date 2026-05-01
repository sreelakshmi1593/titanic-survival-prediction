# Titanic Survival Prediction 🚢

## Overview
Machine learning project to predict which passengers survived the Titanic disaster.
Built using Python, Pandas, and Scikit-learn.

## Results
| Model | Accuracy |
|-------|----------|
| Logistic Regression | 79.89% |
| Decision Tree | 79.89% |
| Random Forest | 82.68% ✅ Best |

## Key Findings from EDA
- **Sex** was the strongest survival predictor — females had much higher survival rates
- **Fare** (wealth) was second most important
- **Age** was third — children were prioritized
- 3rd class passengers had significantly lower survival rates

## Tech Stack
- Python 3.10
- Pandas, NumPy — data manipulation
- Matplotlib, Seaborn — data visualization
- Scikit-learn — machine learning models

## Project Steps
1. Loaded and explored Titanic dataset (891 passengers, 12 features)
2. Performed EDA with visualizations (gender, class, age analysis)
3. Cleaned data — handled missing values, encoded categorical columns
4. Trained 3 ML models and compared accuracy
5. Evaluated best model with confusion matrix and classification report
6. Analyzed feature importance
