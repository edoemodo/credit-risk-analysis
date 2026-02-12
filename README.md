# Credit Risk Analysis & Loan Default Prediction

A data science project analyzing peer-to-peer lending data to predict loan defaults and assess credit risk.

## Project Overview

This project aims to build a predictive model to assess credit risk and identify factors that contribute to loan defaults using real-world lending data from Lending Club (A peer-to-peer lending platform based in the US). 

I have devised a **business objective**, which is to develop a classification model to predict loan default probability and create risk assessment framework for better lending decisions.

## Initial Questions

- What factors are most predictive of loan defaults?
- Can we build an accurate model to predict default risk before loan approval?
- How can we optimize approval thresholds to minimize losses while maximizing approved loans?
- What is the financial impact of false positives vs false negatives?

## Dataset

**Source:** [Lending Club Loan Data (Kaggle)](https://www.kaggle.com/datasets/wordsforthewise/lending-club)

**Size:** ~2.9 million loan applications from 2007-2018

**Key Features:**
- Loan amount, interest rate, and grade
- Borrower income, employment length, and DTI ratio
- Credit history and FICO score
- Loan purpose and term
- Default status (target variable)

## 🛠️ Technologies Used

- **Python 3.9+**
- **Data Analysis:** pandas, numpy
- **Visualization:** matplotlib, seaborn
- **Machine Learning:** scikit-learn
- **Environment:** Jupyter Notebooks


## 📊 Analysis Workflow

### 1. Exploratory Data Analysis
- Data quality assessment
- Distribution analysis of key features
- Default rate analysis by loan characteristics
- Correlation analysis

### 2. Feature Engineering
- Debt-to-income ratio calculations
- Credit utilization metrics
- Payment history indicators
- Risk category creation

### 3. Model Development
- Train/test split with temporal validation
- Handle class imbalance (SMOTE, class weights)
- Model comparison: Logistic Regression, Random Forest, XGBoost
- Hyperparameter tuning

### 4. Model Evaluation
- Precision-recall trade-offs
- ROC-AUC analysis
- Cost-benefit analysis
- Feature importance interpretation

### 5. Business Recommendations
- Risk-based pricing strategies
- Optimal approval thresholds
- Portfolio risk assessment

## Key Results

- To be determined

## Model Performance

- To be determined

## Business Insights

- To be determined

## License

This is a personal portfolio project. Feel free to reference for learning purposes.

## Author

**Edward Budiman**
- GitHub: [@edoemodo](https://github.com/edoemodo)
- LinkedIn: https://www.linkedin.com/in/edwardfbudiman/

## Acknowledgments

- Lending Club, providing the dataset
- Kaggle community, discussions and insights

---

