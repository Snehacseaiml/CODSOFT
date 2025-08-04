# Iris Flower Classification 🌸

This project involves classifying iris flowers into three species — Setosa, Versicolor, and Virginica — based on the length and width of their petals and sepals. As part of my **Data Science Internship at CodSoft**, this classic supervised learning task helped me understand fundamental machine learning workflows and model evaluation.

---

## 📌 Objective

To build a classification model that can accurately predict the species of an iris flower using its features. This is a multi-class classification problem using the well-known **Iris dataset**.

---

## 📁 Project Structure

IRIS_FLOWER_CLASSIFICATION/
│
├── IRIS_FLOWER_CLASSIFICATION.ipynb # Main Jupyter notebook
├── README.md # Project documentation
├── images/ # (Optional) Visualizations & plots
└── requirements.txt # Python dependencies


---

## 🧠 Dataset Features

- `SepalLengthCm` – Sepal length in centimeters  
- `SepalWidthCm` – Sepal width in centimeters  
- `PetalLengthCm` – Petal length in centimeters  
- `PetalWidthCm` – Petal width in centimeters  
- `Species` – Target class (Setosa, Versicolor, Virginica)

---

## 📊 Exploratory Data Analysis (EDA)

- Distribution plots of all features  
- Pairplots and scatter matrices to understand feature relationships  
- Class balance analysis  
- Correlation heatmap to identify feature importance

---

## 🛠️ Model Building

Trained multiple models using **scikit-learn**:
- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Decision Tree Classifier  
- Support Vector Machine (SVM)

---

## 📈 Model Evaluation

Used the following metrics to evaluate model performance:
- Accuracy Score  
- Confusion Matrix  
- Classification Report (Precision, Recall, F1-Score)  
- Cross-validation (optional)

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/CODSOFT.git
   cd CODSOFT/IRIS_FLOWER_CLASSIFICATION
Install dependencies:
pip install -r requirements.txt
Launch the notebook:
jupyter notebook IRIS_FLOWER_CLASSIFICATION.ipynb

🔍 Results
Best Accuracy: ~96–98% (varies slightly by model)

Top Performers: SVM and KNN showed high accuracy with minimal overfitting

Visualization showed clear separation among classes using Petal dimensions

💡 Key Learnings
Hands-on with multi-class classification

Model comparison using multiple metrics

Importance of feature scaling and visualization

Built a complete end-to-end machine learning pipeline

🧰 Tools & Libraries Used
Python 3.x

pandas, numpy

seaborn, matplotlib

scikit-learn

Jupyter Notebook

🔗 Repository Link

