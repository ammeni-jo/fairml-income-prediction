# fairml-income-prediction
# 🌍 Transparency and Fairness in Machine Learning

This project analyzes **bias**, **fairness**, and **model explainability** using the **Adult Census Income dataset**. It evaluates how a logistic regression model might behave unfairly with respect to sensitive features like **gender** and applies **bias mitigation techniques** to address this.

## 📊 Dataset

Adult Census Income Dataset  
- Source: UCI ML Repository  
- Task: Predict whether a person earns `>50K` per year  
- Features include age, race, sex, education, occupation, etc.

## ✅ Key Steps

- 📥 Data loading and preprocessing  
- 🔍 Exploratory Data Analysis (EDA)  
- ⚙️ Baseline model (Logistic Regression)  
- 📈 Performance Evaluation  
- 🧮 Fairness Metrics using `fairlearn`  
- 🛠️ Bias Mitigation using Threshold Optimizer  
- 🔎 Explainability with SHAP values  

## 💡 Insights

- **Fairness trade-off**: Improving Demographic Parity increased Equalized Odds difference.
- **Model bias** was evident in predicting high-income individuals, especially with respect to gender.
- **SHAP values** helped explain feature importance and model decision pathways.

## 🧪 Libraries Used

- `pandas`, `numpy`, `scikit-learn`
- `fairlearn`, `aif360`
- `shap`, `seaborn`, `matplotlib`

## 🔧 Run it Yourself

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/fairness-transparency-ml.git
   cd fairness-transparency-ml
