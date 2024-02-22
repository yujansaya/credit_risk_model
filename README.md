# credit_risk_model
Create a model to predict which clients are more likely to default on their loans.
Kaggle competition

This project entails the development of a comprehensive machine learning pipeline for credit risk assessment. Here's a breakdown of the key components and techniques employed:

Data Loading and Preprocessing:

Parquet files containing heterogeneous data are read and processed using the Polars library.
Data preprocessing steps include setting data types, handling date columns, and filtering irrelevant features based on missing values and uniqueness.
Feature Engineering:

The data is enriched through feature engineering, where multiple datasets are joined and aggregated at varying depths based on relational dependencies.
Feature engineering involves creating new features, extracting meaningful information, and aggregating relevant statistics to improve model performance.
Model Training and Evaluation:

A voting ensemble model comprising LightGBM classifiers is trained using stratified group k-fold cross-validation.
Evaluation metrics such as ROC AUC are utilized to assess model performance on the training data.
Model Interpretation:

Interpretability of the models is enhanced through feature importance analysis and understanding the drivers behind credit risk predictions.
Model Selection and Deployment:

The best-performing model is selected based on evaluation metrics and saved for future use.
The trained model is applied to predict credit risk on unseen test data, and the results are formatted for submission.
The project showcases proficiency in:

Data preprocessing and feature engineering techniques tailored for heterogeneous datasets.
Ensemble modeling strategies for robust predictive performance.
Utilization of advanced libraries like Polars and LightGBM for efficient data processing and modeling.
Adherence to best practices in model evaluation, interpretation, and deployment.
By encapsulating these components into a cohesive pipeline, this project demonstrates competence in developing end-to-end machine learning solutions for complex real-world problems in the financial domain.
