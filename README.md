# 📊 Kaggle Logbook — Grace Eso

A record of my data science journey through competitions and projects.

---

## 🏆 Competition Log

### 1. Titanic - Machine Learning from Disaster
- **Date:** April 2026
- **Type:** Binary Classification
- **Model Used:** Logistic Regression
- **Validation Accuracy:** 81%
- **Kaggle Score:** 0.76315
- **Key Findings:**
  - Women survived significantly more than men
  - First class passengers had better survival odds
  - Age and fare also contributed to survival
- **What I Learned:**
  - Handling missing values (Age, Cabin, Embarked)
  - Encoding categorical variables
  - Train/test split and model evaluation
- **Next Steps:** Try Random Forest to improve score

---

## 📁 Projects
| Project | Type | Score | Date |
|---------|------|-------|------|
| Titanic Survival Prediction | Classification | LR: 0.76315 / RF: 0.74641 | April–May 2026 |

2. Titanic - Machine Learning from Disaster (Model Comparison)
Date: May 2026
Type: Binary Classification
Models Used: Logistic Regression vs Random Forest

| Model | Train Accuracy | Kaggle Score |
|-------|---------------|--------------|
| Logistic Regression | 80.06% | 0.76315 |
| Random Forest (n_estimators=100) | 97.89% | 0.74641 |

Key Findings:
- Random Forest severely overfit the training data (97.89% train vs 0.74641 test)
- Logistic Regression generalized better despite lower training accuracy
- High training accuracy does not guarantee better test performance

What I Learned:
- Overfitting: a model can memorize training data and fail on unseen data
- Model complexity must be balanced with generalization
- Always compare train accuracy vs test score, not just train accuracy alone

Next Steps: Moving to next Kaggle competition
