## CIND-820
Capstone Assignment

## Credit Risk Classification Project

This project was completed as part of the capstone course (CIND 820) in the Certificate in Data Analytics, Big Data & Predictive Analytics program at Toronto Metropolitan University.

The goal of this project is to build a classification model to predict whether a credit applicant is a good or bad credit risk. It uses basic supervised machine learning techniques and is designed to help build foundational skills in model development, evaluation, and interpretation — especially as they relate to real-world applications in financial risk and AML.


## Dataset

- **Name:** German Credit Data  
- **Source:** UCI Machine Learning Repository  
- **Link:** [German Credit Data on UCI](https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data))
- The dataset includes 1,000 credit applicants and 20 features, such as credit history, loan purpose, age, employment status, housing type, etc.
- The target variable (`credit_risk`) is binary: `1` for good risk, `2` for bad risk. This was converted to `1` (good) and `0` (bad) during preprocessing.


## Tools & Libraries

- Python  
- Google Colab  
- pandas, NumPy  
- scikit-learn  
- matplotlib (planned for later phases)  


## Project Stages

1. Data Loading:** Mounted Google Drive and loaded the dataset from a `.data` file  
2. Preprocessing:** Label encoding for categorical features, target conversion, and feature scaling  
3. Model Training:** Trained three classifiers:
   - Logistic Regression  
   - Decision Tree  
   - Naive Bayes  
4. Evaluation:** Compared models using:
   - Accuracy  
   - Recall  
   - Confusion matrix  
   - 5-fold cross-validation  
5. Initial Results:** Logistic Regression achieved the best performance with ~76% accuracy and 0.864 recall  
6. Next Steps:** Feature importance analysis, visualization, and further evaluation (e.g. precision, F1 score)


## Summary of Results

| Model              | Accuracy | Recall | Cross-Val Accuracy |
|-------------------|----------|--------|---------------------|
| Logistic Regression | 0.76     | 0.864  | 0.76                |
| Decision Tree       | 0.715    | 0.764  | 0.684               |
| Naive Bayes         | 0.76     | 0.807  | 0.726               |

The results confirm that simple classification models, when properly prepared and evaluated, can provide useful insights into creditworthiness.


## Future Improvements

- Add precision, F1 score, and ROC curves  
- Visualize feature importances and model comparisons  
- Add support for additional algorithms (e.g. Random Forest or XGBoost)  
- Improve class balance handling using SMOTE or reweighting  


## Repository Contents

- `cind820_credit_risk.ipynb`: Main notebook with code and results  
- `german.data`: Raw dataset  
- `README.md`: Project overview  
- `initial_results_summary.rtf`: Draft text for report  
- `final_report.pdf`: (To be added at the end of capstone)  
- `video_walkthrough.mp4`: (To be added)


## Author

**Strahinja Nakic**  
Certificate in Data Analytics, Big Data & Predictive Analytics  
Toronto Metropolitan University  
