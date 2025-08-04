# Titanic Survival Prediction 🚢

This is my first project as a **Data Science Intern at CodSoft**, where I built a machine learning model to predict the survival of passengers on the Titanic using the classic Titanic dataset. The project involves data preprocessing, exploratory data analysis (EDA), feature engineering, and training multiple machine learning models to evaluate performance.

---

## 📁 Project Structure

Titanic-Survival-Prediction/
│
├── data/                  # Dataset files (train.csv, test.csv, etc.)
├── notebooks/             # Jupyter Notebooks for EDA & modeling
├── models/                # Saved models (if any)
├── images/                # Screenshots or visualizations
├── requirements.txt       # Python libraries used
├── README.md              # This file
└── .gitignore             # Ignored files (e.g. checkpoints, models)

---

## 📌 Problem Statement

Given passenger data (such as age, sex, class, fare, etc.), predict whether they survived the Titanic disaster. This is a binary classification task using supervised machine learning algorithms.

---

## 📊 Features Used

- `Pclass` – Ticket class (1st, 2nd, 3rd)
- `Sex` – Gender of the passenger
- `Age` – Age in years
- `SibSp` – Number of siblings/spouses aboard
- `Parch` – Number of parents/children aboard
- `Fare` – Fare paid
- `Embarked` – Port of embarkation (C, Q, S)
- `Cabin` – Cabin number (used partially for feature engineering)
- `FamilySize` – Combined family members aboard
- `IsAlone` – Whether the passenger was traveling alone

---

## 🧠 Workflow

1. **Data Loading & Cleaning**
   - Handled missing values (Age, Embarked, Cabin)
   - Dropped unnecessary columns (e.g., Ticket, Name)

2. **Exploratory Data Analysis (EDA)**
   - Used Seaborn & Matplotlib for visual insights
   - Analyzed survival rates based on gender, class, age, etc.

3. **Feature Engineering**
   - Created new features: `FamilySize`, `IsAlone`, etc.
   - Encoded categorical variables using One-Hot and Label Encoding

4. **Modeling**
   - Applied various ML models using scikit-learn:
     - Logistic Regression
     - Decision Tree Classifier
     - Random Forest Classifier
     - K-Nearest Neighbors
   - Evaluated using accuracy, confusion matrix, and classification report

5. **Model Comparison**
   - Compared performance metrics to select the best model

---

## 🚀 How to Run the Project

1. Clone this repository:
   ```bash
   Titanic_Survival_Prediction.ipynb
   
pip install -r requirements.txt
jupyter notebook notebooks/Titanic_EDA_Modeling.ipynb
📈 Results
Best Model: Random Forest Classifier

Accuracy: ~85% on test data

Key Insight: Gender and class were highly influential in survival probability

📦 Tech Stack
Python 3.x

Jupyter Notebook

pandas, numpy

matplotlib, seaborn

scikit-learn

📚 Learnings
Hands-on experience with data preprocessing and EDA

Improved understanding of feature engineering and model tuning

Learned how to evaluate and compare ML models effectively

First exposure to presenting a professional data science project

🔗 GitHub Repository
