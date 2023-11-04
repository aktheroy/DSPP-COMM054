# DSPP-COMM054
Breast Cancer Classification

🔬 Project: Breast Cancer Classification

📊 Dataset: 683 instances, 9 features

🎯 Objective: Distinguish benign (0) from malignant (1) cells using Logistic Regression and Naïve Bayes.

Steps:

🛠️ Data Preprocessing:
Ensured data integrity through duplicate removal.
Applied standard normalization and min-max scaling.
Evaluated feature relationships (Pearson's Correlation Coefficient), leading to 'cell_shape' exclusion.

🔄 Cross-validation:
Implemented Stratified K-Fold (k=10) for balanced evaluation.

📈 Results:
Naive Bayes outperformed Logistic Regression, attributed to its efficacy in feature-independent scenarios.

⚙️ Considerations:
The effectiveness of a machine learning model hinges on the specific problem domain.
Thus, rigorous model comparison is crucial. Simplicity and computational efficiency are vital, especially for large datasets and real-time predictions.
