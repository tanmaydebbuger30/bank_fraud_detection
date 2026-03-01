# Bank Fraud Detection (Machine Learning)

End-to-end Machine Learning project to detect potentially fraudulent banking transactions using supervised classification in Python.  
Includes data preprocessing, model training & evaluation, hyperparameter tuning, and saving the best-performing model for inference.

## Project Highlights
- Data cleaning + preprocessing (missing values, encoding, scaling as needed)
- Train/test split with reproducibility
- Multiple model experiments (baseline + tuned model)
- Evaluation using key fraud metrics (Precision, Recall, F1, ROC-AUC, Confusion Matrix)
- Best model exported as a serialized artifact for reuse

---

## Repository Structure
```text
ML-Banking_Frayd_Prediction/
│── main.py                          # Training / inference runner (project entry)
│── banking_fraud_predication.ipynb  # Notebook: EDA + modeling walkthrough
│── best_fraud_model_tune.pkl        # Saved best model (local artifact; do not push if large)
│── data.csv                         # Dataset (should NOT be pushed to GitHub if >100MB)
│── Assigment Task.pdf               # Project task description (optional)
│── .gitignore                       # Ignore large and local files
