# 🛠 Predictive Maintenance Classifier

This project builds and evaluates machine learning models to predict equipment failure states using sensor and operational data. It leverages classification algorithms, feature engineering, and interpretability tools to support proactive maintenance decisions.

## 📦 Project Overview

- **Goal**: Predict failure categories (e.g., normal, warning, critical) from machine data
- **Models Used**: Random Forest, Gradient Boosting
- **Techniques**:
  - Categorical encoding and feature binarization
  - Cross-validation and fold-wise accuracy visualization
  - Confusion matrix for diagnostic evaluation
  - Feature importance comparison across models
  - SHAP values for global and local interpretability

## 🧠 Workflow Summary

1. **Data Preprocessing**
   - Encode categorical variables
   - Handle missing values
   - Binarize continuous targets for classification

2. **Model Training**
   - Fit Random Forest and Gradient Boosting classifiers
   - Evaluate using cross-validation and confusion matrices

3. **Interpretability**
   - Compare feature importances across models
   - Use SHAP to explain individual predictions and global trends

## 📊 Key Insights

- Feature importance reveals which inputs (e.g., `cycle_count`, `load_intensity`) drive failure predictions
- SHAP values provide transparency for model decisions, enabling trust and actionable maintenance alerts

## 🚀 Future Enhancements

- Add time-to-failure regression or survival analysis
- Deploy model as a REST API or dashboard
- Integrate real-time sensor streaming for live predictions

## 🧰 Tech Stack

- Python (pandas, scikit-learn, matplotlib, seaborn, SHAP)
- Jupyter Notebook / VS Code
- Optional: Flask or FastAPI for deployment

---
