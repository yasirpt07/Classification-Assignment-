# 🧠 Breast Cancer Classification using Supervised Learning

This project applies supervised machine learning algorithms to classify tumors as **malignant** or **benign** using the **Breast Cancer Wisconsin** dataset from `sklearn.datasets`.

---

## 🎯 Objective

The goal of this assessment is to evaluate and compare the performance of various classification algorithms on a real-world medical dataset.

---

## 📊 Dataset

- **Source**: `sklearn.datasets.load_breast_cancer()`
- **Instances**: 569
- **Features**: 30 numeric features
- **Target**: Binary (0 = malignant, 1 = benign)

---

## 🛠️ Preprocessing Steps

- Checked for missing values (none found).
- Standardized the features using `StandardScaler` to normalize data.
- Split the dataset into training and testing sets (80/20).

---

## 🧪 Algorithms Used

Each model was trained, tested, and evaluated using **accuracy** and a **classification report**.

1. **Logistic Regression**  
2. **Decision Tree Classifier**  
3. **Random Forest Classifier**  
4. **Support Vector Machine (SVM)**  
5. **k-Nearest Neighbors (k-NN)**  

> Each model includes a brief explanation and justification within the notebook.

---

## 📈 Results

| Model                | Accuracy |
|---------------------|----------|
| Logistic Regression | 0.9737   |
| Decision Tree       | 0.9298   |
| Random Forest       | 0.9649   |
| SVM                 | 0.9737   |
| k-NN                | 0.9561   |

- ✅ **Best Model**: Logistic Regression / SVM (tie)
- ❌ **Lowest Accuracy**: Decision Tree

-----
