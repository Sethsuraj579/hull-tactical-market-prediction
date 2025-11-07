# 📈 ML Prediction Pipeline with CSV Input

This repository demonstrates a simple machine learning workflow using Python and scikit-learn. It trains a model on `train.csv`, makes predictions on `test.csv`, and exports the results to `predictions.csv`.

---

## 🧰 Project Overview

- Load and preprocess CSV data
- Train a Random Forest classifier
- Predict outcomes on test data
- Export predictions to a new CSV file

---

## 📁 Dataset Format

### `train.csv`
| Feature Columns | Target Column |
|-----------------|----------------|
| X1, X2, ..., Xn | target          |

### `test.csv`
| Feature Columns |
|-----------------|
| X1, X2, ..., Xn |

---

## 🚀 How to Run

### 1. Install Dependencies

```bash
pip install pandas scikit-learn
