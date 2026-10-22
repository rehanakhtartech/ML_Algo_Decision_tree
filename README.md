# Decision Tree Algorithms: ID3, C4.5 & CART 🌳

## 📌 Project Overview

This project explores three popular Decision Tree algorithms used in Machine Learning: **ID3, C4.5, and CART**.

The goal is to understand how these algorithms select features, split data, and build decision trees for classification tasks.

## 🎯 Objectives

- Understand the working principles of decision tree algorithms.
- Learn Information Gain, Gain Ratio, and Gini Impurity.
- Compare the splitting methods used by different algorithms.
- Apply decision tree concepts using Python.
- Understand how decision trees make predictions.

## 🧠 Algorithms Covered

### 1. ID3 (Iterative Dichotomiser 3)
- Uses **Information Gain** to select the best feature.
- Commonly creates multiway splits.
- Primarily designed for classification.

### 2. C4.5
- Uses **Gain Ratio** to select splitting features.
- Extends ID3 by supporting continuous attributes and handling missing values.
- Includes pruning to help reduce overfitting.

### 3. CART (Classification and Regression Trees)
- Uses binary splits.
- Commonly uses **Gini Impurity** for classification.
- Supports both classification and regression.
- Uses pruning to help control overfitting.

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- Machine Learning fundamentals

## 📊 Key Concepts

| Concept | Purpose |
|---|---|
| Entropy | Measures uncertainty in data |
| Information Gain | Measures the reduction in entropy after a split |
| Gain Ratio | Adjusts Information Gain using Split Information |
| Gini Impurity | Measures class impurity in a dataset |
| Pruning | Reduces unnecessary branches to help prevent overfitting |

## ⚙️ Installation

Install the required libraries:

```bash
python -m pip install pandas scikit-learn
```

## 🚀 How to Run

Run your Python script from the terminal:

```bash
python train_and_compare.py
```

Replace `train_and_compare.py` with your actual Python filename if it is different.

## 📚 What I Learned

- How decision trees divide datasets into smaller groups.
- How Information Gain, Gain Ratio, and Gini Impurity differ.
- How decision tree algorithms select features for splitting.
- How to use Python and Scikit-learn for classification.
- Why pruning and controlling tree depth are important.

## 🔮 Future Improvements

- Compare the algorithms using the same dataset.
- Evaluate accuracy, precision, recall, and F1-score.
- Visualize the generated decision trees.
- Experiment with different tree depths and pruning methods.

## 👨‍💻 Author

AI/ML Student | Exploring Machine Learning through practical projects

