# Task 11 — Comparative Analysis of Classification Models

**Internship:** PKCERT AI & Software Development Internship
**Intern:** Mahin (Reg. No. 230201012, Batch CS 04B)
**Institute:** Islamabad Institute of Technology

## Objective
Build, train, and compare three classification models — Logistic Regression, Random Forest, and Support Vector Machine (SVM) — on a common dataset, then evaluate and recommend the best-performing model.

## Dataset
**Wine Recognition Dataset** (`sklearn.datasets.load_wine`)
- 178 samples, 13 numeric chemical features
- Target: wine cultivar (3 classes)
- No missing values

## Contents
| File | Description |
|---|---|
| `Task11_Classification_Model_Comparison.ipynb` | Executed Jupyter notebook with all four parts |

## Structure of the Notebook
- **Part A — Dataset Selection & Preparation:** dataset description, EDA (class distribution, correlation heatmap), feature scaling, 80/20 stratified train-test split
- **Part B — Model Development:** Logistic Regression, Random Forest, and SVM trained on identical preprocessed data
- **Part C — Model Evaluation & Comparison:** Accuracy, Precision, Recall, F1-Score, confusion matrices, comparison table & chart, strengths/weaknesses discussion
- **Part D — Recommendation & Conclusion:** best model identified by macro F1-score with justification

## How to Run
```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
jupyter notebook Task11_Classification_Model_Comparison.ipynb
```
Run all cells top to bottom — the notebook is self-contained and loads the dataset directly from scikit-learn (no external files needed).

## Tools & Libraries
Python, NumPy, Pandas, Matplotlib, Seaborn, scikit-learn
