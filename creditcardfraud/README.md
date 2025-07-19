## Credit Card Fraud Detection

This project uses Machine Learning to detect fraudulent transactions from a highly imbalanced credit card dataset. Built as part of CodSoft Internship Program.
## How It Works

- Uses the [Kaggle Credit Card Fraud Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Scales transaction amount using `StandardScaler`
- Trains a `RandomForestClassifier` with `class_weight='balanced'`
- Allows testing by entering transaction index number (like 541)

## Files

| File                  | Description                            |
|-----------------------|----------------------------------------|
| `CreditCardFraud.ipynb` | Notebook with training + prediction logic |
| `fraud_model.pkl`       | Saved trained Random Forest model     |
| `scaler.pkl`            | Saved StandardScaler for Amount column |
| `requirements.txt`      | Python dependencies                  |

---

## Example Output

```text
Enter transaction index (0 to 284806): 541

Transaction Amount: ₹ 1.0
Prediction: FRAUD
Actual Label: FRAUD

