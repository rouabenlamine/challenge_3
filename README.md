# challenge_3
Support Ticket Topic Classification
# Customer Support Text Classification

This project builds a simple multi-class text classification system that categorizes short customer support messages into:

- Billing
- Technical
- Account

The model uses:
- TF-IDF (Term Frequency – Inverse Document Frequency)
- Logistic Regression

---

## How It Works

1. Load a dataset containing customer messages.
2. Split data into training and testing sets.
3. Convert text into numerical features using TF-IDF.
4. Train a Logistic Regression classifier.
5. Evaluate performance using accuracy and confusion matrix.
6. Test the model with new input messages.

---

## Requirements

Install the required libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

---

## Dataset Format

Your CSV file must contain:

| Column | Description |
|--------|------------|
| text   | Customer message |
| label  | Billing / Technical / Account |

---


## Example

Input:
```
I was charged twice this month
```

Output:
```
Predicted Category: Billing
```

---

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib

Simple traditional NLP approach for multi-class classification.
