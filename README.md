# 💰 Financial Risk Classification

This project demonstrates how to predict financial loan default risk using ensemble machine learning models on a real-world credit dataset. We apply Random Forest, AdaBoost, and Gradient Boosting classifiers to build predictive models and evaluate their performance.

---

## 📊 Project Overview

**Goal**: Predict whether a credit applicant is a *good* or *bad* risk.

**Dataset**: [German Credit Dataset](https://raw.githubusercontent.com/selva86/datasets/master/GermanCredit.csv)

**Tech Stack**:
- Python (Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib)
- Jupyter Notebook
- Ensemble Learning (Random Forest, AdaBoost, Gradient Boosting)

---

## 📁 Key Steps

1. **Data Preprocessing**
   - Handle categorical features via one-hot encoding
   - Standardize numerical features

2. **Exploratory Data Analysis (EDA)**
   - Target class distribution
   - Feature correlation heatmap

3. **Modeling**
   - Train/test split
   - Random Forest, AdaBoost, Gradient Boosting
   - Classification reports & confusion matrices

4. **Evaluation**
   - Model accuracy comparison
   - Visual insights via heatmaps and bar plots

---

## 📈 Results

All three ensemble models were evaluated on their classification performance:

| Model              | Accuracy |
|-------------------|----------|
| Random Forest      | ~78–85%  |
| AdaBoost           | ~75–82%  |
| Gradient Boosting  | ~77–84%  |

---

## 📎 Usage

```bash
# Clone this repo
git clone https://github.com/your-username/financial-risk-classification.git
cd financial-risk-classification

# Open the notebook
jupyter notebook financial_risk_classification.ipynb
