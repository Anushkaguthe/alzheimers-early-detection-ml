# alzheimers-early-detection-ml
## Problem Statement
Alzheimer's is a progressive neurodegenerative disorder. 
Early detection enables timely intervention and better 
patient outcomes.

## Dataset
- 2,149 patient records
- 35 clinical features
- Source: Kaggle

## Approach
1. Data preprocessing and feature engineering
2. Class imbalance handling using SMOTE
3. Feature selection using correlation, chi-square 
   and mutual information
4. Model training and comparison
## Models Used
| Model | Accuracy | ROC AUC |
|---|---|---|
| Logistic Regression | 82.1% | 0.90 |
| Random Forest | 91.4% | 0.96 |
| Gradient Boosting | 93.3% | 0.97 |

## Key Results
- Best model: Gradient Boosting
- Accuracy: 93.3%
- ROC AUC: 0.97
- False Negatives minimized to 36 out of 415 cases

## Technologies Used
Python, Scikit-learn, Pandas, NumPy, 
Matplotlib, Seaborn, Imbalanced-learn

## Future Enhancements
- Add MRI/CT scan features for better accuracy
- Add SHAP values for model explainability
- Try XGBoost and LightGBM
- Deploy as web app
