# 🌸 KNN from Scratch: Iris Flower Classification

## 📘 Overview
This project implements the K-Nearest Neighbors (KNN) algorithm **from scratch** to classify the Iris flower dataset. To validate correctness, results are compared with scikit-learn’s `KNeighborsClassifier`.

KNN is a **supervised machine learning** method that predicts the class of a test point based on the most frequent class among its `k` nearest neighbors, using distance calculations (here, Euclidean distance).

---

## 📁 Dataset
- **Dataset**: Iris Flower Dataset  
- **Source**: Available directly in `sklearn.datasets`  
- **Classes**:
  - Setosa (0)
  - Versicolor (1)
  - Virginica (2)

---

## 🧹 Preprocessing Steps
1. Loaded the Iris dataset using `load_iris()` from scikit-learn.  
2. Split the data into **70% training** and **30% testing** using `train_test_split`.  
3. Used all four numeric features for classification:
   - Sepal Length
   - Sepal Width
   - Petal Length
   - Petal Width

---

## 🧠 Modeling
- **Model Used**: K-Nearest Neighbors implemented manually  
- **k**: 3  
- **Distance Metric**: Euclidean distance  
- **Voting**: Majority vote among neighbors  
- **Comparison**: Scikit-learn `KNeighborsClassifier` with the same parameters

---

## 🧪 Evaluation Metrics

### 🌸 From-Scratch KNN Results
| Metric     | Value  |
|------------|--------|
| Accuracy   | 1.0    |
| Precision  | ≈ 1.0  |
| Recall     | ≈ 1.0  |
| F1 Score   | ≈ 1.0  |

- **Confusion Matrix**:
### 🤖 scikit-learn KNN Results
Perfect classification with identical metrics:  
- Accuracy: 1.0  
- Precision: 1.0  
- Recall: 1.0  
- F1-score: 1.0

---

✅ **Author**: Md Mahmudul Hasan Rifat  
🆔 **Student ID**: 222002048  
📘 **Course**: CSE312 - Section 222D3  
📝 **Lab Report 02**
