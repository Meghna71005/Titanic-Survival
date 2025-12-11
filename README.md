## Titanic Survival Prediction – Kaggle Competition 🚢

This repository contains my complete workflow for the **Kaggle Titanic: Machine Learning from Disaster competition**.
The goal is to build a model that predicts which passengers survived the Titanic sinking.This repository showcases **feature engineering, model comparison, cross-validation, and Kaggle submission workflow**.

**Dataset from Kaggle Titanic: Machine Learning from Disaster**

## Project Highlights ⭐

| Metric                        | Score                                  |
| ----------------------------- | -------------------------------------- |
| **Cross-Validation Accuracy** | **0.83273**                            |
| **Final Kaggle Score**        | **0.78229**                            |
| **Leaderboard Rank**          | **Top ~4,000 of 10,000+ participants** |


**Tech Stack**: Python, Pandas, NumPy, Scikit-learn, XGBoost


**Approach**: Extensive feature engineering + model comparison + hyperparameter tuning


## What I Learned 📚

- Handling missing data effectively
- Creating meaningful engineered features
- Comparing ML algorithms
- Cross-validation & model selection
- Preparing Kaggle submission files


## Feature Engineering Used 🔧

The notebook includes the following engineered variables:

- Title extraction from names
- FamilySize
- IsAlone
- Fare per person (FarePP)
- Cabin category (Cabin_F)
- TicketGroupSize
- Age imputation + AgeBand
- Encoding categorical features
- Scaling numerical features


## Models Compared 🤖

| Model                   | Notes                        |
| ----------------------- | ---------------------------- |
| **Logistic Regression** | Baseline model               |
| **Random Forest**       | *Best model* (0.78229 score) |
| **XGBoost**             | Slightly lower performance   |


**Best model: Random Forest + Feature Engineering (0.78229 Kaggle score)**


 ## Repository Structure 📁

📦 Titanic-Survival-Prediction

     ├── 📓 titanic_survival_notebook.ipynb
     
     ├── 📄 submission.csv
     
     ├── 📄 README.md
     
     ├── 📁 data
     
          ├──train.csv
          
          ├──test.csv

 ## How to Run ▶️
pip install -r requirements.txt
jupyter notebook

📌 Acknowledgements

Kaggle Titanic Competition

Community notebooks & discussions
