# Pipeline in Machine Learning

**Overview**

This repository demonstrates how to implement a Machine Learning Pipeline using the Pipeline library. The goal is to simplify and accelerate the model training and prediction process while efficiently handling data preprocessing with ColumnTransformer.

**Why Use Pipelines?**

1) Automates data preprocessing and model training steps.
2) Reduces code redundancy and improves maintainability.
3) Ensures consistency in transformations applied to both training and test data.
4) Enhances efficiency by combining multiple preprocessing steps into a single pipeline.

**Libraries**

The following libraries are used in this implementation:
1) sklearn.pipeline (for Pipeline, make_pipeline)
2) sklearn.preprocessing (for StandardScaler, OneHotEncoder)
3) sklearn.impute (for SimpleImputer)
4) sklearn.compose (for ColumnTransformer)
5) sklearn.decomposition (for PCA)
6) sklearn.linear_model (for LogisticRegression, as an estimator)

**Implementation Steps**
1) Load the Dataset – Import and split the dataset into training and testing sets.
2) Define Preprocessing Steps – Handle missing values, scale numerical data, and encode categorical features.
3) Build the Pipeline – Combine preprocessing steps with an estimator using Pipeline.
4) Train the Model – Fit the pipeline on the training data.
5) Make Predictions – Use the trained pipeline for predictions on new data.

**Conclusion**

Using Pipelines and ColumnTransformer in scikit-learn helps streamline the machine learning workflow. This approach ensures that preprocessing and model training are applied consistently, leading to more efficient and maintainable code.
