**Learning Outcomes – Chapter 2: End-to-End Machine Learning Project**

1. **Problem Framing**

- Learned how to clearly define the machine learning task
- Supervised vs Unsupervised
- Regression vs Classification
- Batch vs Online learning
- Defining input features and target variable

2. **Selecting the Right Performance Metric**

- Understood why RMSE was chosen
- Learned how performance metrics must align with business objectives

3. **Importance of Train/Test Split**

- Test set must remain untouched
- Splitting must be done before preprocessing
- Understanding stratified sampling
- Preventing data leakage

4. **Exploratory Data Analysis (EDA)**

- Visualizing data distributions
- Analyzing correlations
- Understanding feature relationships
- Gaining insights before modeling

5. **Handling Missing Data**

- Dropping rows or columns
- Median imputation
- Using Scikit-Learn imputers
- Applying transformations inside pipelines

6. **Handling Categorical Attributes**

- One-hot encoding
- Avoiding false ordinal relationships
- Converting categorical data into numerical form

7. **Feature Scaling**

- Min-Max Scaling
- Standardization
- Understanding sensitivity to outliers
- Knowing when scaling is necessary

8. **Pipelines**

- Automating preprocessing steps
- Preventing data leakage
- Ensuring reproducibility
- Maintaining consistent transformations

9. **Model Evaluation and Comparison**

- Comparing multiple models systematically
- Evaluating models using proper metrics

10. **Cross-Validation**

- Using k-fold cross-validation
- Obtaining reliable performance estimates
- Reducing evaluation bias

11. **Hyperparameter Tuning**

- Grid Search
- Randomized Search
- Tuning on validation data instead of test data

12. **Avoiding Overfitting**

- Understanding model complexity
- Recognizing bias vs variance trade-off
- Ensuring good generalization

13. **Data Leakage Awareness**

- Never fitting preprocessors on the full dataset
- Never tuning on the test set
- Keeping evaluation unbiased

14. **End-to-End Machine Learning Workflow**

- Frame
- Explore
- Prepare
- Train
- Validate
- Tune
- Evaluate
