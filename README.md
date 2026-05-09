# Loan Interest Rate Prediction
### Linear Regression with Gradient Descent | BFSI Case Study

A machine learning model that predicts loan interest rates
based on credit scores using Linear Regression with Gradient
Descent, built from scratch using NumPy and Pandas.

---

## Problem Statement
A bank wants to automate interest rate decisions based on
applicant credit scores.

- **X (Input):** Credit Score (300–900)
- **Y (Output):** Interest Rate (%)
- **Relationship:** Inverse — higher score = lower rate

---

## Project Structure
| File | Description |
|------|-------------|
| bfsi_regression.ipynb | Full Jupyter notebook |
| outputs/ | All charts and plots |
| report/ | Final PDF submission |

---

## Results
| Metric | Value |
|--------|-------|
| MAE    | ~0.70 |
| MSE    | ~0.80 |
| RMSE   | ~0.90 |
| R²     | ~0.95 |

---

## Key Insight
For every 1-point rise in credit score, interest rate drops
consistently. A borrower improving score from 400 to 800
can save lakhs over a loan tenure.

---

## Libraries Used
- NumPy
- Pandas
- Matplotlib
- Scikit-learn (metrics only)
