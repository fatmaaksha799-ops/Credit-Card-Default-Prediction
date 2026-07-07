# Credit Card Default Prediction

A machine learning project that predicts whether a credit card customer is likely to default on their payment, using classification models trained on customer financial data.

## 📌 Problem Statement

Banks and financial institutions need to identify customers who are at risk of defaulting on credit payments so they can take early action — such as adjusting credit limits or offering support — to reduce financial losses. This project builds a predictive model to flag high-risk customers based on their financial profile.

## 📊 Dataset

The dataset contains customer-level financial information, including:
- Income
- Loan amount
- Loan-to-Income ratio
- Credit history / other financial indicators
- Target variable: `Default` (1 = defaulted, 0 = did not default)

## 🔍 Approach

1. **Data Exploration (EDA)** — checked for class imbalance, visualized feature distributions, and examined correlations between features and default status using a heatmap and boxplots.
2. **Preprocessing** — handled missing values and prepared features for modeling.
3. **Modeling** — trained a classification model (Logistic Regression) to predict default risk.
4. **Evaluation** — assessed model performance using accuracy and other classification metrics.

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn (visualization)
- Scikit-learn (modeling)
- Jupyter Notebook

## 📈 Key Insight

Loan-to-Income ratio showed the strongest relationship with default risk — customers with higher loan-to-income ratios were significantly more likely to default.

## 🚀 How to Run

1. Clone this repository
```bash
   git clone https://github.com/fatmaaksha799-ops/Credit-Card-Default-Prediction.git
```
2. Open `credit-card-default-prediction.ipynb` in Jupyter Notebook or VS Code
3. Install required libraries:
```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
```
4. Run all cells

## ⚠️ Limitations & Future Work

- Only one classification algorithm was tested; comparing multiple models (e.g. Random Forest, XGBoost) could improve accuracy
- Class imbalance was observed but not explicitly corrected (e.g. via SMOTE)
- Feature set is limited; additional financial indicators could improve prediction quality

## 👤 Author

Aksha Fatma — B.Tech CSE, 6th Semester
