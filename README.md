# 🧪 Breast Cancer Classification using Support Vector Machine (SVM)

This project uses a Support Vector Machine (SVM) with an RBF kernel to classify tumors as **malignant** or **benign** using the **Breast Cancer Wisconsin Dataset**. It includes scaling, cross-validation, and hyperparameter tuning with different regularization strengths (C values).

---

## 🔍 What's Included

- Loads the `breast_cancer` dataset from `sklearn.datasets`
- Scales features using `StandardScaler`
- Trains an SVM classifier with RBF kernel
- Performs 5-fold cross-validation
- Evaluates accuracy across different `C` values
- Visualizes performance trends to choose the best `C`

---

## 📈 Visualization

The notebook generates a plot showing:

- Mean cross-validation accuracy
- Standard deviation of performance
- Behavior across different regularization strengths (log scale)

---

## 🛠️ How to Run

1. Clone the repository:

```
git clone https://https://github.com/NoorNick/Breast-Cancer-Detection.git
cd Breast-Cancer-Detection
```

2. Install dependencies:
```
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:

```
jupyter notebook
```
Open breast_cancer_svm.ipynb and run all cells.

---
## 🧪 Example Output
```
Cross-validation scores: [0.9561 0.9649 0.9386 0.9649 0.9737]
Mean CV score: 0.960 (+/- 0.025)

```
---
Support early detection. Classify responsibly. 🎗️
