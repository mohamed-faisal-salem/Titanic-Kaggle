# 🚢 Titanic - Kaggle Machine Learning Competition

This project is my solution to the **Kaggle Titanic competition**, where I achieved **Top 9%** on the public leaderboard.

The notebook focuses on **clean feature engineering**, **proper preprocessing**, and **model tuning** using classical machine learning models.

---

## 📊 Dataset
- Source: Kaggle Titanic Dataset
- Size: 891 rows × 12 features
- Target: `Survived` (binary classification)

> The dataset is **not included** in this repository.  
> Please download it directly from Kaggle.

---

## 🧠 Approach

### 1️⃣ Exploratory Data Analysis (EDA)
- Understanding survival patterns
- Analyzing features like `Sex`, `Pclass`, `Age`, `Fare`

### 2️⃣ Feature Engineering
- Handling missing values using **group-based statistics**
  - Example: Filling `Age` using median per `Pclass`
- Encoding categorical variables
- Feature scaling where appropriate

### 3️⃣ Modeling
The following models were trained and tuned using **cross-validation**:

- Random Forest Classifier
- Gradient Boosting Classifier

Hyperparameters were optimized using **GridSearchCV** with stratified folds.

---

## 🧪 Evaluation
- Metric: **Accuracy**
- Cross-validation used to avoid overfitting
- Best model selected based on validation performance

---

## 🏆 Result
- **Top 9%** on Kaggle Titanic competition leaderboard

This result was achieved by focusing on **feature engineering and proper model validation**, not deep learning.

---

## ▶️ How to Run Locally

1. Download the dataset from Kaggle:
   https://www.kaggle.com/c/titanic

2. Create a folder called `data/` and place:
   - `train.csv`
   - `test.csv`

3. Run the notebook:
```bash
jupyter notebook titanic-top9%.ipynb
