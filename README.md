# Title: Diagnosing-heart-disease-using-machine-learning

#Idea of Project:
This research presents a practical, data-driven solution to enhance early detection of heart disease using machine learning algorithms. Given the alarming global mortality rates attributed to heart conditions, particularly coronary artery disease and arrhythmia, the need for intelligent, non-invasive, and cost-effective diagnostic alternatives has become urgent. Traditional methods often involve lengthy and expensive clinical procedures that delay diagnosis and limit access to timely intervention. Therefore, this study leverages the predictive power of machine learning (ML) to construct automated diagnostic models capable of identifying heart disease from medical data.

Using the Cleveland Heart Disease dataset, which includes features such as age, sex, blood pressure, cholesterol, electrocardiographic results, and heart rate, the research implements four popular classification algorithms: Support Vector Machine (SVM), Random Forest, LightGBM, and XGBoost. These models are trained and tested to predict the presence of heart disease with high accuracy. The goal is to identify the most reliable and efficient classifier, offering clinicians a powerful tool for preliminary diagnosis, particularly in under-resourced environments. This solution represents a bridge between healthcare and artificial intelligence, empowering early prevention and effective medical intervention.

#Components:
The system is built around a robust machine learning pipeline that includes data acquisition, preprocessing, feature selection, model training, evaluation, and result analysis. The key components and their roles are:

Dataset: Cleveland Heart Disease dataset (303 entries, 14 features), sourced from Kaggle.

Preprocessing: Includes data cleaning, normalization (e.g., using StandardScaler), and encoding of categorical variables.

Feature Selection: Utilized SelectKBest with ANOVA F-value (f_classif) to reduce dimensionality and focus on the top 10 most predictive features.

# Machine Learning Models:

Support Vector Machine (SVM): Achieved the highest accuracy (90%) and balanced performance across all metrics.

Random Forest Classifier: Performed well (89% accuracy), especially in minimizing false positives.

LightGBM: Efficient gradient boosting model with 86.89% accuracy, optimized for speed.

XGBoost: Powerful but underperformed in this context (79% accuracy), with high false negative rates.

# Evaluation Metrics: Accuracy, precision, recall, F1-score, confusion matrix, and classification reports were used to assess model performance.

# Implementation Platform: Python using libraries like Scikit-learn, XGBoost, LightGBM, Pandas, and Matplotlib/Seaborn for data visualization.

This framework not only ensures model reliability but also provides interpretability, scalability, and real-world applicability for healthcare institutions.

# Author: Waleed Manea Saleh
