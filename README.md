# Titanic-Kaggle-

## Overview
This project predicts passenger survival on the Titanic using machine learning, achieving **82% accuracy**. 
It demonstrates end-to-end ML pipeline development including data cleaning, feature engineering, model selection, and hyperparameter tuning.

## Key 
- **82% accuracy** using ensemble methods (Random Forest + Gradient Boosting)
- Engineered 15+ predictive features from raw passenger data
- Implemented cross-validation and grid search for robust model selection
- Ranked in top [X]% on Kaggle leaderboard

## 🛠️ Technologies Used
- Python (Pandas, NumPy, Scikit-learn)
- Data Visualization (Matplotlib, Seaborn)
- Jupyter Notebooks for EDA
- Git for version control

## Key Insights 
1. **Gender** was the strongest predictor (80% of females survived vs 20% of males)
2. **Passenger class** significantly impacted survival (1st class: 63%, 3rd class: 24%)
3. **Family size** showed non-linear effects (small families: 50%+, alone: 30%)
4. **Title** (Mr/Mrs/Miss/Master) captured both gender and marital status

## Pipeline Summary 
1. **Data Cleaning**: Handling missing values from various features such as Age, Cabin, Embarked
2. **Feature Engineering**: Creating Title, FamilySize, FarePerPerson, etc.
3. **Model Training**: ComparingLogistic Regression, Decision Trees, Random Forest, Gradient Boosting
4. **Ensemble**: Combining best models for improved performance
5. **Submission**: Generating predictions for Kaggle competition

## Results
| Model | Accuracy |
|-------|----------|
| Logistic Regression | 80.1% |
| Decision Tree | 81.7% |
| Random Forest | 82.3% |
| Gradient Boosting | 82.5% |
| **Ensemble** | **82.8%** |

## 🚀 How to Run
```bash
git clone https://github.com/yourusername/titanic-ml-project
cd titanic-ml-project
pip install -r requirements.txt
python src/train_model.py
