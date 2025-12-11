## Titanic Survival Prediction – Kaggle Competition

This repository contains my complete workflow for the Kaggle Titanic: Machine Learning from Disaster competition.
The goal is to build a model that predicts which passengers survived the Titanic sinking.

## Project Highlights

Cross-Validation Accuracy: 0.83273
Final Kaggle Score: 0.78229

Ranking: Top ~4k out of 10,000+

Tech Stack: Python, Pandas, NumPy, Scikit-learn, XGBoost

Approach: Extensive feature engineering + model comparison + hyperparameter tuning

## What I Learned

Handling missing data effectively

Creating meaningful engineered features

Comparing ML algorithms

Cross-validation & model selection

Preparing Kaggle submission files

## Features Engineered

The notebook includes the following engineered variables:

Title extraction from names

FamilySize

IsAlone

Fare per person (FarePP)

Cabin category (Cabin_F)

TicketGroupSize

Age imputation + AgeBand

Encoding categorical features

Scaling numerical features

## Models Compared

Logistic Regression

Random Forest

XGBoost


Best model: Random Forest + Feature Engineering (0.78229 Kaggle score)

📁 Repository Structure
📦 Titanic-Survival-Prediction
├── 📓 titanic_survival_notebook.ipynb
├── 📄 submission.csv
├── 📄 README.md
└── 📁 data
     ├── train.csv
     ├── test.csv

▶️ How to Run
pip install -r requirements.txt
jupyter notebook

📌 Acknowledgements

Kaggle Titanic Competition

Community notebooks & discussions