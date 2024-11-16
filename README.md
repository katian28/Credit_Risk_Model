# Predicting Credit Risk for Underserved Populations

Exploring how socioeconomic factors like income, education, and employment history influence credit risk for individuals with limited credit history. Using machine learning techniques, we aim to develop fair and interpretable models that can inform equitable lending practices, leveraging AI4ALL’s innovative program framework.

---

## Problem Statement <!--- do not change this line -->

Credit risk assessment traditionally disadvantages individuals with less than one year of credit history, limiting their access to financial resources. This project seeks to uncover the relationship between socioeconomic factors and credit risk, focusing on underserved populations, to enable more inclusive lending practices and mitigate biases that perpetuate inequality.

---

## Key Results <!--- do not change this line -->

1. Identified the most influential socioeconomic factors affecting credit risk for individuals with limited credit history.
2. Built interpretable and high-performing machine learning models, including logistic regression, Random Forest, and XGBoost, achieving an accuracy of over 80% on the test set.
3. Implemented fairness-aware techniques to address historical, representation, and measurement biases in the dataset.

---

## Methodologies <!--- do not change this line -->

1. **Data Preprocessing**:
   - Filtered the dataset to focus on individuals with less than one year of credit history.
   - Handled missing values using multiple imputation techniques.
   - Balanced the dataset using reweighting and synthetic data generation to address underrepresentation.

2. **Model Development**:
   - Trained logistic regression for interpretability and ensemble methods (Random Forest, XGBoost) for capturing non-linear patterns and improving predictive accuracy.
   - Evaluated models based on accuracy, precision, recall, F1 score, and fairness metrics.

3. **Bias Mitigation**:
   - Used adversarial debiasing and fairness-aware sampling techniques to minimize biases in model outcomes.

4. **Analysis**:
   - Visualized feature importance and socioeconomic patterns using Python libraries like matplotlib and seaborn.

---

## Data Sources <!--- do not change this line -->

- **Kaggle**: [Credit Card Approval Prediction Dataset](https://www.kaggle.com/)
- Supplementary research:
  - World Bank: Financial Inclusion
  - S&P Global: Machine Learning and Credit Risk Modelling

---

## Technologies Used <!--- do not change this line -->

- **Programming Languages**: Python
- **Libraries/Frameworks**:
  - `scikit-learn`
  - `pandas`
  - `numpy`
  - `xgboost`
  - `matplotlib`
  - `seaborn`
- **Tools**: Jupyter Notebook

---

## Authors <!--- do not change this line -->

This project was completed in collaboration with:
- **Serafina Wang**, **Megane Alexis**, **Praise Manzi**, **Katia Nkurunziza**, **Mariam Lomishvili**, **Mosopefoluwa John**


For questions or contributions, please contact ux.
