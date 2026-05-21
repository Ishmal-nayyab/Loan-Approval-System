# Loan Approval Prediction using Decision Tree

## Project Overview
This project focuses on building a binary classification Machine Learning model using a **Decision Tree Classifier** to automate the process of loan approval. The model analyzes applicant profiles to accurately predict whether a loan application should be **Approved** or **Rejected** based on historical patterns.

## Dataset Features Analyzed
The dataset contains key variables influencing loan assessment, including:
- `Gender`, `Married`, `Dependents`, `Education`, `Self_Employed`
- `ApplicantIncome`, `CoapplicantIncome`, `LoanAmount`, `Loan_Amount_Term`, `Credit_History`, `Property_Area`
- **Target Variable:** `Loan_Status` (Y / N)

## Key Pipeline Steps in the Notebook
- **Exploratory Data Analysis (EDA):** Performed initial structural analysis and visualized distributions of approvals.
- **Data Preprocessing & Cleaning:**
  - Handled missing data points using rows dropping (`dropna`).
  - Applied **Label Encoding** to transform qualitative categorical features into quantitative numerical representations.
- **Feature & Target Segmentation:** Separated independent features ($X$) from the ground-truth prediction target ($y$).
- **Data Splitting:** Partitioned the preprocessed dataset into training and testing sets using a 70/30 stratified ratio to maintain evaluation integrity.
- **Model Training & Evaluation:** Programmed, trained, and validated a `DecisionTreeClassifier` using `scikit-learn` to test accuracy against the unseen test subset.

## Tech Stack & Libraries Used
- **Language:** Python
- **Data Engineering:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning Architecture:** Scikit-Learn

## How to View and Run
1. Open the notebook `Decision_Tree (2).ipynb` directly on GitHub to view code execution blocks and statistical outputs.
2. To replicate or run locally, clone this repository:
   ```bash
   git clone [https://github.com/your-username/Loan-Approval-Prediction.git](https://github.com/your-username/Loan-Approval-Prediction.git)
