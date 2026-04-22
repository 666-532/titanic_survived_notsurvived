# Titanic Survival Prediction 🚢

## Overview
Predicting survival of Titanic passengers
using Decision Tree Classifier.

## Dataset
- Source: Kaggle Titanic Dataset
- Rows: 891
- Target: Survived (0 or 1)

## Steps Performed
- Exploratory Data Analysis (EDA)
- Handling Missing Values
- Feature Encoding
- Decision Tree Model
- Hyperparameter Tuning (max_depth, criterion)
- Feature Importance

## Results
| Model | Training Score | Testing Score |
|---|---|---|
| Decision Tree (default) | 98.17% | 81.56% |
| Decision Tree (max_depth=3) | 82.58% | 80.44% |
| Decision Tree (GridSearchCV) | --% | --% |

## Libraries Used
- Python
- Pandas
- Scikit-learn
- Matplotlib

## How to Run
1. Clone the repo
2. Install requirements: pip install -r requirements.txt
3. Open titanic_decision_tree.ipynb
4. Run all cells
