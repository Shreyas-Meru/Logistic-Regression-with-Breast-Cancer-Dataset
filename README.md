# 🧠 Logistic Regression on Breast Cancer Dataset

This repository showcases a binary classification project using **Logistic Regression** on the **Breast Cancer Wisconsin Diagnostic Dataset**. The goal is to predict whether a tumor is **malignant** or **benign** based on various features extracted from digitized images of breast masses.

---

## 📁 Dataset

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))
- **Target classes**:
  - `0`: Malignant
  - `1`: Benign

---

## 🔧 Workflow

1. Load and explore the dataset
2. Train/Test split
3. Standardize features using `StandardScaler`
4. Train a **Logistic Regression** model
5. Evaluate using:
   - Confusion Matrix
   - Precision, Recall, F1-score
   - **ROC-AUC score** and ROC Curve
6. Tune classification threshold
7. Explain the **sigmoid function**

---

## 📊 Model Performance (Default Threshold 0.5)

- **Accuracy**: 98%
- **Precision (Benign)**: 97%
- **Recall (Benign)**: 100%
- **ROC-AUC Score**: 0.998

---

## 📈 Sigmoid Function

The logistic regression model uses the sigmoid activation function to map predictions to a probability between 0 and 1:

\[
\sigma(z) = \frac{1}{1 + e^{-z}}
\]

- This output can be interpreted as the probability of class 1.
- By default, predictions with probability ≥ 0.5 are classified as class 1.
- You can **tune the threshold** to balance between false positives and false negatives.

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Shreyas-Meru/Logistic-Regression-with-Breast-Cancer-Dataset.git
   cd Logistic-Regression-with-Breast-Cancer-Dataset
   ```

2. Run the Jupyter notebook:
   ```bash
   jupyter notebook
   ```

---

## 📦 Requirements

- Python 3.7+
- scikit-learn
- pandas
- matplotlib
- numpy


## 🙌 Acknowledgments

- [Scikit-learn](https://scikit-learn.org/)
- [UCI ML Repository](https://archive.ics.uci.edu/)
```
