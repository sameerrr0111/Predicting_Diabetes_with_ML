# Predicting Diabetes with Machine Learning 🚑🤖

This project is part of my Machine Learning coursework — my goal was to move beyond theory and build a hands-on, end-to-end ML pipeline to predict diabetes using real-world medical data.

---

## 📌 Project Overview

- **Objective:** Predict whether a patient has diabetes based on diagnostic health data.
- **Approach:** Data exploration, cleaning, preprocessing, training multiple models, and comparing their performance.
- **Models Compared:** Logistic Regression, Decision Tree, Random Forest, XGBoost.
- **Best Performing Model:** XGBoost — 83% accuracy, F1-Score 0.80.

---

## 🗂️ Dataset

The dataset includes medical features such as:
- Age
- BMI
- HbA1c Level
- Blood Glucose
- And other relevant diagnostic attributes.

*Note: Add the dataset source here if it’s public. If it’s private or course-provided, mention that too.*

---

## 🔍 What I Did

- **Data Cleaning:** Removed duplicates, handled missing values.
- **EDA:** Visualized distributions and relationships between key features and the target variable.
- **Preprocessing:** Applied scaling and encoding.
- **Model Building:** Trained four models using scikit-learn and XGBoost.
- **Evaluation:** Compared models using Accuracy, Precision, Recall, F1-Score, ROC-AUC.
- **Analysis:** Checked for overfitting and the impact of training data size.

---

## ✅ Results

| Model               | Accuracy | F1-Score |
|---------------------|----------|----------|
| Logistic Regression | 78%      | 0.735    |
| Decision Tree       | 74%      | 0.69     |
| Random Forest       | 82%      | 0.78     |
| XGBoost             | 83%      | 0.80     |

**XGBoost** achieved the best overall performance.

---

## 📊 Visuals

The notebook includes:
- Feature distribution plots
- Confusion matrices for all four models
- Model comparison charts
- F1-Score vs Training Data Size analysis

---

## ⚙️ Technologies Used

- Python
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## 🚀 Getting Started

To run the project locally:

1. **Clone the repository**
   ```bash
   git clone [YOUR_REPO_LINK]
2. Open the code in VS Code or any other editor.

3. Install the dependencies
   ```bash
    pip install -r requirements.txt
4. Load the dataset
  Place your dataset file (e.g., diabetes_prediction_dataset.csv) in the working directory.

5. Run the notebook
  Open the .ipynb file in Jupyter Notebook or VS Code and run all cells step by step.

