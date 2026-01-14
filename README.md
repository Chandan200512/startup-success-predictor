# Startup Success Predictor

An end-to-end machine learning project that predicts whether a startup will
**succeed or fail** using funding, investor presence, industry, and geographic data
from Crunchbase-style datasets.

---

## 📌 Problem Statement
Predict startup success based on structured business features to help
investors and founders assess risk.

### Success Definition
- **Success (1):** Acquired or IPO
- **Failure (0):** Closed

---

## 📊 Dataset
- Source: Kaggle (Crunchbase-style startup dataset)
- Records: Thousands of startups
- Target variable: `success`

---

## Features Used
- Funding metrics (`funding_total_usd`, `funding_rounds`)
- Investor presence (`has_vc`, `has_angel`)
- Geography (`is_ca`, `is_ny`, `is_ma`, etc.)
- Industry (`category_code`)
- Startup age metrics
- Top 500 indicator (`is_top500`)

---

##Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## Model
- **Logistic Regression**
- Class imbalance handled using `class_weight='balanced'`

---

## Evaluation Metrics
- Precision
- Recall
- F1-score
- ROC-AUC

---

## Key Insights
- Higher funding and multiple funding rounds increase success probability
- Startups with VC/Angel backing perform better
- Geography and industry significantly influence outcomes
- Logistic Regression offers strong interpretability for business decisions

---

## 🧪 How to Run
1. Open the notebook in Kaggle or Jupyter
2. Run all cells top to bottom
3. Ensure dataset path is correct

---

## 📌 Future Improvements
- Try advanced models (XGBoost, Random Forest)
- Add model deployment using Streamlit
- Perform feature importance visualization

---

## Author
**Chandan.NG
Aspiring Data Scientist AI| ML Engineering
