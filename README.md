# Fraud-Transaction-Detection
Detect fraudulent transactions using a provided, real-world dataset of 150,000 financial records. This project focuses on applying exploratory data analysis (EDA), feature engineering, and advanced classification models to accurately identify fraudulent behavior.
---

## 📊 Project Overview

**Objective:**  
Detect fraudulent transactions in a provided, real-world dataset of 150,000 financial records. This project focuses on applying exploratory data analysis (EDA), feature engineering, and advanced classification models to accurately identify fraudulent behavior and reduce financial risk.

---

## Tools & Techniques
- Python (Pandas, NumPy, Scikit-learn, Imbalanced-learn)
- Jupyter Notebook
- Data visualization (Matplotlib, Seaborn)
- Classification models (Logistic Regression, Random Forest, XGBoost)
- Evaluation metrics (Precision, Recall, F1-score)

---

## Key Steps
- Analyzed transaction patterns and identified distinguishing fraud features
- Engineered new features to improve model learning
- Applied multiple classification algorithms and compared performance
- Handled severe class imbalance using resampling and weighting techniques
- Evaluated models using precision, recall, F1-score, and ROC-AUC
- Visualized results with ROC curves, confusion matrices, and feature importance plots

---

## Key Insights from Model

- **Model_Performance:**  
Achieved high recall on fraudulent cases, balancing sensitivity and precision to minimize both false positives and false negatives, critical in fraud detection.

- **Feature_Impact:**  
Identified key transaction characteristics (such as amount patterns, frequency, and anomalies) most indicative of fraud, improving model interpretability and actionable value.

- **Business_Insight:**  
Highlighted behavioral and transactional trends distinguishing fraudulent activity, offering practical insights for improving fraud monitoring systems.

- **Visual_Takeaways:**  
ROC curves and confusion matrices provided clear, interpretable evaluations of model performance, guiding optimization choices and model selection.

---

## Project Files
- `fraud_detection_model.ipynb` → Main Jupyter notebook with full analysis and modeling
- `fraud_data/` → Dataset files
- `plots/` → Visual outputs (ROC curves, confusion matrices, feature importance)

---

## Outcome
Demonstrated the ability to tackle high-stakes, real-world problems by detecting rare fraudulent transactions in a large, imbalanced dataset. Combined strong technical modeling with critical thinking to balance precision and recall, ensuring the solution was both technically sound and business-relevant. Delivered clear, interpretable insights that could help stakeholders reduce financial losses and improve operational decision-making.
