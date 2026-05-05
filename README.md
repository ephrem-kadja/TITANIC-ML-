# 🚢 Titanic Survival Prediction — Machine Learning Project

## 📌 Project Overview

This project aims to predict whether a passenger survived the Titanic disaster using machine learning techniques.

It follows a structured ML workflow:

* Exploratory Data Analysis (EDA)
* Data Cleaning
* Feature Engineering
* Model Training & Evaluation

---

## 🎯 Objective

Build a supervised machine learning model to predict:

> **Survived (0 = No, 1 = Yes)**

---

## 📊 Dataset

The dataset is provided by Kaggle:

* `train.csv` → training data (with labels)
* `test.csv` → test data (without labels)
* `gender_submission.csv` → example submission

---

## 🧠 Workflow

### 1. Exploratory Data Analysis (EDA)

* Understanding dataset structure
* Identifying missing values
* Analyzing relationships between features and target
* Key insights:

  * Women had higher survival rates
  * Higher class passengers survived more
  * Strong interaction between Sex and Pclass

---

### 2. Data Cleaning

* Handling missing values:

  * `Age` → filled using statistical strategy
  * `Embarked` → filled with most frequent value
  * `Cabin` → removed (high missing rate)

---

### 3. Feature Engineering

Creation of new meaningful features:

* `FamilySize = SibSp + Parch + 1`
* `IsAlone`
* `AgeGroup`
* Interaction between features

---

### 4. Data Preprocessing

* Encoding categorical variables:

  * Sex → numerical
  * Embarked → one-hot encoding
* Feature scaling (if required)

---

### 5. Model Training

* Logistic Regression (baseline model)

---

### 6. Evaluation

* Accuracy
* Confusion Matrix
* Precision / Recall

---

### 7. Future Improvements

* Random Forest
* Gradient Boosting (XGBoost)
* Hyperparameter tuning
* Advanced feature engineering

---

## ⚙️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

## 📁 Project Structure

```
titanic-ml-project/
│
├── data/
│   ├── train.csv
│   ├── test.csv
│
├── notebooks/
│   └── v1_Titanic_Logistic_Regression.ipynb
│
├── src/
│   └── (cleaning, preprocessing, model)
│
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

1. Clone the repository
2. Install dependencies:

```
pip install -r requirements.txt
```

3. Run the notebook or scripts

---

## 📈 Key Insight

Survival is strongly influenced by:

* Gender
* Passenger class
* Social structure during evacuation

---

## 🧠 Learning Outcome

This project demonstrates:

* End-to-end machine learning workflow
* Data preprocessing techniques
* Feature engineering strategies
* Model evaluation

---

## 📌 Author

EPHREM KADJA 
