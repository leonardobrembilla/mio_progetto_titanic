# 🚢 Titanic Survival Prediction with Machine Learning

## 📌 Project Overview

This project was developed as part of the **Start2Impact University – Machine Learning** course.

The objective is to predict whether a passenger survived the Titanic disaster using supervised Machine Learning techniques. The project follows a complete Data Science workflow, including data exploration, preprocessing, feature engineering, model training, hyperparameter tuning, and performance evaluation.

---

## 📂 Dataset

**Dataset:** Titanic Dataset

The dataset contains information about passengers aboard the Titanic, including:

- Passenger Id
- Sex
- Age
- Pclass
- Embarked
- Survived (target variable)

**Target Variable**

- `Survived`
  - 0 = Did not survive
  - 1 = Survived

---

## 📊 Exploratory Data Analysis (EDA)

The exploratory analysis includes:

- Dataset overview
- Missing values analysis
- Age distribution
- Survival rate by gender
- Survival rate by passenger class
- Statistical summaries

The visualizations help understand the main relationships between the variables before building the predictive model.

---

## ⚙️ Data Preprocessing

The preprocessing pipeline includes:

- Train/Test Split
- Missing value imputation
- Numerical feature scaling using **StandardScaler**
- Categorical encoding using **OneHotEncoder**
- ColumnTransformer
- Scikit-learn Pipeline

This approach avoids data leakage and guarantees that all preprocessing steps are applied consistently.

---

## 🤖 Machine Learning Model

The final model used is:

- Decision Tree Classifier

Hyperparameters were optimized using **GridSearchCV** to identify the best tree configuration.

---

## 📈 Model Evaluation

The model performance is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

These metrics provide a comprehensive evaluation of the classifier's predictive performance.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📁 Project Structure

```
├── LeonardoBrembillaMLI.ipynb
├── README.md
├── requirements.txt
└── titanic_sub.csv

```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/titanic-machine-learning.git
```

2. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Open the notebook

```bash
jupyter notebook LeonardoBrembillaMLI.ipynb
```

or open it directly using **Google Colab**.

---

## 🎯 Learning Objectives

This project demonstrates the ability to:

- Perform Exploratory Data Analysis
- Handle missing values
- Build preprocessing pipelines
- Prevent data leakage
- Train and optimize Machine Learning models
- Evaluate classification performance
- Follow Data Science best practices

---

## 👨‍💻 Author

**Leonardo Brembilla**

Data Scientist

GitHub: https://github.com/leonardobrembilla

LinkedIn: https://www.linkedin.com/in/leonardobrembilla

---

## 📄 License

This project was created for educational purposes as part of the Start2Impact University Machine Learning course.
