# Logistic Regression Binary Classification

## 🔍 Objective
This project demonstrates binary classification using **Logistic Regression** on the **Breast Cancer Wisconsin Dataset**.

---

## 📊 Dataset
**Source**: [Breast Cancer Wisconsin (Diagnostic) Data Set](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)

- Features: 30 numeric attributes related to cell nuclei from digitized images.
- Target: `diagnosis` - Malignant (M) or Benign (B)

---

## 🔧 Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## 📌 Steps Followed
1. Loaded and preprocessed the dataset.
2. Split the data into training and testing sets.
3. Scaled features using StandardScaler.
4. Trained a **Logistic Regression** model.
5. Evaluated using:
   - Confusion Matrix
   - Precision, Recall, F1-Score
   - ROC-AUC Curve
6. Tuned threshold for performance analysis.

---

## 📈 Evaluation Metrics

| Metric              | Description |
|---------------------|-------------|
| **Confusion Matrix** | Shows true/false positives/negatives |
| **Precision**       | TP / (TP + FP) |
| **Recall**          | TP / (TP + FN) |
| **ROC-AUC**         | Probability that classifier ranks a random positive higher than a negative |

---

## 📐 Sigmoid Function
The **sigmoid** function maps real values to probabilities between 0 and 1:

