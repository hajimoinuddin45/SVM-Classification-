# 🧬 SVM Classification – Breast Cancer Dataset

This repository contains my solution for **Task 7: Support Vector Machines (SVM)** using the Breast Cancer Dataset from sklearn.

---

## 🎯 Objective

- Train and evaluate SVM models with **linear** and **RBF (non-linear)** kernels.
- Visualize decision boundaries using PCA.
- Tune and evaluate hyperparameters (C, gamma).

---

## 🛠 Tools Used

- Python
- Scikit-learn
- NumPy, Pandas
- Matplotlib

---

## ✅ What I Did

1. Loaded the Breast Cancer dataset (binary classification).
2. Standardized the dataset using `StandardScaler`.
3. Applied PCA to reduce dimensions to 2 for plotting.
4. Trained SVM with both **linear** and **RBF** kernels.
5. Visualized decision boundaries.
6. Evaluated performance using accuracy, confusion matrix, classification report.
7. Applied cross-validation to test model generalization.

---

## 📊 Results

- **Linear SVM Accuracy:** ~[your accuracy]
- **RBF SVM Accuracy:** ~[your accuracy]
- **Best Accuracy (RBF):** Achieved better separation than linear kernel in this case.

---

## 🧠 What I Learned

- SVM separates classes by **maximizing the margin**.
- RBF Kernel is great for non-linear decision boundaries.
- Tuning **C** and **gamma** significantly affects performance.
- **PCA** helps in visualizing high-dimensional data in 2D.

---

## 📁 Files

- `task7_svm_classification.ipynb`
- `README.md`

---

## 📦 Dataset

- Breast Cancer Dataset from `sklearn.datasets.load_breast_cancer()`

---

Feel free to clone and experiment with different kernels and parameters!
