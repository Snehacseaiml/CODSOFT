# Credit Card Fraud Detection 🔍💳

This project focuses on detecting fraudulent transactions from a credit card dataset using machine learning techniques. As part of my internship at **CodSoft**, this task provided valuable hands-on experience with imbalanced datasets, classification models, and real-world data challenges.

---

## 📌 Objective

To build a classification model that can accurately detect fraudulent credit card transactions from anonymized data. This is a binary classification problem with a strong class imbalance (fraud cases are rare).

---

## 📁 Project Structure

CREDIT_CARD_FRAUD_DETECTION/
│
├── CREDIT_CARD_FRAUD_DETECTION.ipynb # Main notebook
├── README.md # Project documentation
├── data/ # (Optional) dataset folder
├── models/ # (Optional) saved models
├── images/ # Visualizations and plots
└── requirements.txt # List of dependencies


---

## 🧠 Key Features Used

- `Time` – Time elapsed since the first transaction
- `V1` to `V28` – PCA-transformed anonymized features
- `Amount` – Transaction amount
- `Class` – Target variable (0: Non-Fraud, 1: Fraud)

---

## 🧪 Workflow

### 1. Data Preprocessing
- Handled data imbalance using **SMOTE** (Synthetic Minority Oversampling)
- Scaled `Amount` and `Time` features using **StandardScaler**

### 2. Exploratory Data Analysis (EDA)
- Analyzed distribution of fraud vs. non-fraud
- Visualized correlations and feature distributions

### 3. Model Building
Trained and evaluated multiple classification models:
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost (optional)

### 4. Model Evaluation
- Accuracy
- Precision, Recall, F1-Score
- Confusion Matrix
- ROC-AUC Curve

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   
Install the dependencies:
pip install -r requirements.txt
Launch the Jupyter Notebook:
jupyter notebook CREDIT_CARD_FRAUD_DETECTION.ipynb

📊 Results
Best Model: [e.g., Random Forest / XGBoost]

Accuracy: ~99.3%

Recall: Prioritized to reduce false negatives

ROC AUC Score: ~0.98+

💡 Key Learnings
Handling highly imbalanced datasets

Importance of Recall and Precision in fraud detection

Practical use of SMOTE and scikit-learn pipelines

Evaluation metrics beyond just accuracy

🧰 Tools & Libraries Used
Python

pandas, numpy

seaborn, matplotlib

scikit-learn

imbalanced-learn (SMOTE)

🔗 Repository Link
