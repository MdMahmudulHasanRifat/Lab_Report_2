# 📘 KNN from Scratch: Flower Classification with Custom Evaluation Metrics

**Author:** Md Mahmudul Hasan Rifat  
**Student ID:** 222002048  
**Course:** CSE312 - Section 222D3  
**Lab Report:** 02

---

This project implements the **K-Nearest Neighbors (KNN)** classification algorithm from scratch using Python. It also includes custom functions to evaluate the model with metrics such as accuracy, confusion matrix, precision, recall, and F1-score.

The implementation is tested on the classic **Iris flower dataset** and compared with the `scikit-learn` KNN classifier for validation.

---

## 📁 Dataset

- **Dataset**: Iris dataset (built-in in `sklearn.datasets`)  
- **Features**: 4 features per sample (sepal length, sepal width, petal length, petal width)  
- **Classes**: 3 species of Iris flowers

---

## 🧠 Model Details

- **Algorithm**: K-Nearest Neighbors (KNN) from scratch  
- **Distance Metric**: Euclidean distance  
- **Number of Neighbors (`k`)**: 3 (customizable)  
- **Training/Test Split**: 70% training, 30% testing (`random_state=42` for reproducibility)

---

## 🧪 Evaluation Metrics (Custom Implementations)

- **Accuracy**: Proportion of correct predictions  
- **Confusion Matrix**: True vs predicted label counts  
- **Precision**: True positives divided by predicted positives  
- **Recall**: True positives divided by actual positives  
- **F1-Score**: Harmonic mean of precision and recall

---

## ▶️ How to Run

1. Make sure you have Python 3 installed.  
2. Install dependencies using pip:
   ```bash
   pip install numpy scikit-learn
## 📈 Sample Output

🌸 KNN From Scratch Results:
Accuracy: 0.9555555555555556
Confusion Matrix:
[[16 0 0]
[ 0 16 1]
[ 0 1 11]]
Metrics: {'precision': 0.9545454545454545, 'recall': 0.9545454545454546, 'f1_score': 0.9543834046603113}

🤖 Scikit-learn KNN Results:
precision recall f1-score support

markdown
Copy
Edit
       0       1.00      1.00      1.00        16
       1       0.94      0.94      0.94        17
       2       0.92      0.92      0.92        12

accuracy                           0.95        45
macro avg 0.95 0.95 0.95 45
weighted avg 0.95 0.95 0.95 45

