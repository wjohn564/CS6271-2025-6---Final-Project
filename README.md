# Evolutionary Programming – Adult Income Classifier

This project uses **Grammatical Evolution (GE)** to evolve simple, human-readable rules to predict whether a person’s income is above a threshold.

**Dataset Description**
This dataset is designed for a binary classification problem where the goal is to predict whether a person’s annual income exceeds $50K based on demographic and employment attributes. The target variable income takes the value 1 if income > $50K and 0 otherwise.

The dataset contains 39,073 entries with 15 columns, including both numerical and categorical features. It’s inspired by the classic Adult Income dataset, often used for income prediction and fairness analysis tasks.

Feature Description
Column Name	Description
age	Age of the individual
workclass	Type of employment (e.g., Private, Self-emp, Govt, etc.)
fnlwgt	Final sampling weight (demographic significance)
education	Highest level of education achieved
education-num	Numerical representation of education level
marital-status	Marital status (e.g., Married, Single, Divorced)
occupation	Type of occupation or job role
relationship	Relationship status (e.g., Husband, Wife, Unmarried)
race	Race of the individual
sex	Gender of the individual
capital-gain	Capital gains (investment income)
capital-loss	Capital losses (investment losses)
hours-per-week	Average working hours per week
native-country	Country of origin
income	Target variable — 1 if income > $50K, else 0
Files
train.csv - the training set
test.csv - the test set
sample_submission_with_id.csv - a sample submission file in the correct format
