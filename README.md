# Predicting Term Deposit Subscriptions Using Machine Learning

> **Course:** Introduction to Data Science (IDS)  
> **Topic:** Bank Marketing Analytics Case Study

---

## 📌 Project Overview
Direct telemarketing campaigns require substantial staff and financial resources. Predicting customer conversion likelihood helps financial institutions optimize marketing budgets, improve conversion rates, and reduce unnecessary customer calls.

This project analyzes the **Bank Marketing Dataset** (UCI Machine Learning Repository) to identify key demographic, financial, and campaign drivers influencing term deposit subscriptions, and develops predictive classification models to forecast subscription probability (`yes` vs. `no`).

---

## 🎯 Objectives & Methodology
1. **Data Cleaning & Preprocessing:** Address missing values, handle categorical variable encoding, and clean outliers.
2. **Exploratory Data Analysis (EDA):** Identify distributions, key correlations, and feature relationships with customer subscription decisions.
3. **Machine Learning Classifiers:**
   - Logistic Regression
   - Decision Trees (`rpart`)
   - Random Forest (`randomForest`)
4. **Evaluation & Comparison:** Evaluate using Accuracy, Precision, Recall, F1-Score, and ROC-AUC curves.
5. **Business Interpretation:** Develop a targeted outreach ranking strategy based on predicted subscription probabilities.

---

## 📂 Repository Contents

| File | Description |
|---|---|
| `IDS_Case_Study.ipynb` | Interactive Jupyter Notebook containing the full analysis and model execution pipeline |
| `IDS_Term_Deposit_Subscription_Project.Rmd` | Complete R Markdown report containing data preprocessing, EDA, model training, and evaluation |
| `IDS ppt.pptx` | Project presentation slides summarizing problem statement, methodology, and key findings |
| `IDS_Case_Study_Guidelines.docx` | Project evaluation criteria and case study guidelines |
| `IDS_Project_Review_Source_Document.pdf` | Academic review and reference source document |
| `IDS_CaseStudy_Details.xlsx` | Case study metadata and dataset details |

---

## 🚀 How to Run

### Option 1: Jupyter Notebook
1. Open `IDS_Case_Study.ipynb` in VS Code or Jupyter Lab.
2. Run all cells sequentially. The dataset will be automatically downloaded and processed.

### Option 2: R Markdown
1. Open `IDS_Term_Deposit_Subscription_Project.Rmd` in RStudio.
2. Install required packages:
   ```r
   install.packages(c("tidyverse", "caret", "pROC", "rpart", "rpart.plot", "randomForest", "scales", "corrplot"))
   ```
3. Click **Knit** to generate the HTML report.
