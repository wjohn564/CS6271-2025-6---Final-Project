This is a binary classification problem where the target variable `income` is:

- `1` if annual income > \$50K  
- `0` otherwise  

The training set contains **39,073** rows and **15** columns (14 input features + 1 target).  
The dataset is a modified version of the classic Adult Income dataset, commonly used for income prediction and fairness analysis.

---

## Features

| Column           | Description                                                   |
|------------------|---------------------------------------------------------------|
| `age`            | Age of the individual                                        |
| `workclass`      | Type of employment (e.g. Private, Self-emp, Government)      |
| `fnlwgt`         | Final sampling weight (demographic significance)             |
| `education`      | Highest level of education achieved                          |
| `education-num`  | Numerical encoding of education level                        |
| `marital-status` | Marital status (e.g. Married, Single, Divorced)              |
| `occupation`     | Type of occupation or job role                               |
| `relationship`   | Relationship status (e.g. Husband, Wife, Unmarried)          |
| `race`           | Race of the individual                                       |
| `sex`            | Gender of the individual                                     |
| `capital-gain`   | Capital gains (investment income)                            |
| `capital-loss`   | Capital losses (investment losses)                           |
| `hours-per-week` | Average working hours per week                               |
| `native-country` | Country of origin                                            |
| `income`         | **Target** — `1` if income > \$50K, else `0`                 |

---

## Files

- `train.csv` – Training set with features and `income` label  
- `test.csv` – Test set with the same features (no `income` label)  
- `sample_submission_with_id.csv` – Sample submission file showing the required Kaggle format
