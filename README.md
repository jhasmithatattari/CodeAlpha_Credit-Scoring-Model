
# Credit Scoring Model

## Overview

This project is a Machine Learning based **Credit Scoring Model** developed using Python and Scikit-learn.
The model predicts whether a customer is a **Safe Customer** or a **Risky Customer** based on financial and personal information.

The project uses the **German Credit Dataset** and applies a **Random Forest Classifier** for prediction.


# Dataset

Dataset Used:

* German Credit Dataset

Dataset Link:

* [Kaggle German Credit Dataset](https://www.kaggle.com/datasets/uciml/german-credit)

# Features Used
 __ __ __ __ __ __ __ __ __ __ __ __ __ __ __
| Feature          | Description             |
| ---------------- | ----------------------- |
| Age              | Customer age            |
| Sex              | Gender                  |
| Job              | Job category            |
| Housing          | Housing type            |
| Saving accounts  | Savings account status  |
| Checking account | Checking account status |
| Credit amount    | Loan amount             |
| Duration         | Loan duration           |
| Purpose          | Purpose of loan         |
|__ __ __ __ __ __ | __ __ __ __ __ __ __ __ |

# Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn


# Machine Learning Algorithm

* Random Forest Classifier


# Project Workflow

1. Load Dataset
2. Handle Missing Values
3. Encode Categorical Data
4. Create Target Column
5. Split Dataset into Training and Testing Sets
6. Train Random Forest Model
7. Predict Customer Risk
8. Evaluate Model Accuracy


# Installation

Install required libraries using:

```bash
pip install pandas numpy scikit-learn
```


# How to Run

1. Download the dataset
2. Place the CSV file in your project folder
3. Update dataset path in the code
4. Run the Python script

```bash
python credit_scoring.py
```

---

# Sample Code

```python
data["target"] = np.where(data["Credit amount"] > 5000, 1, 0)
```


# Model Evaluation Metrics

The following metrics are used:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix


# Output

The model predicts:

* Safe Customer
  or
* Risky Customer


# Future Improvements

* Use real target labels such as `Risk`
* Improve feature engineering
* Try Deep Learning models
* Deploy using Flask or Streamlit


# Author

Jhasmitha


# License

This project is for educational and learning purposes.
