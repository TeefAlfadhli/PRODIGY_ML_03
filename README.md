# PRODIGY_ML_03
# 🐶🐱 Kaggle Cats vs. Dogs SVM Classifier Project Overview

## 📂 **Project Overview:**
This project aims to classify images of cats and dogs from the Kaggle dataset using a **Support Vector Machine (SVM)**. The implementation explores the impact of **Principal Component Analysis (PCA)** for dimensionality reduction on model performance. The evaluation compares results before and after applying PCA.

## 🛠️ **Workflow:**
1. **Data Preprocessing:** Images were resized and flattened into feature vectors.
2. **Feature Scaling:** Standardized features using `StandardScaler`.
3. **Model Training:** SVM model was trained using both raw and PCA-transformed features.
4. **Evaluation:** Performance was assessed using accuracy, classification reports, and confusion matrices.

---

## 📊 **Results Before PCA:**
### 🧪 **SVM Model Accuracy:** 0.60
```
               precision    recall  f1-score   support
           0       0.67      0.59      0.62        17
           1       0.53      0.62      0.57        13
    accuracy                           0.60        30
```
- **True Positives (Dog):** 10 | **False Positives:** 7
- **True Positives (Cat):** 8 | **False Negatives:** 5

---

## 📊 **Results After PCA:**
### 🧪 **PCA SVM Model Accuracy:** 0.70
```
               precision    recall  f1-score   support
           0       0.79      0.65      0.71        17
           1       0.62      0.77      0.69        13
    accuracy                           0.70        30
```
- **True Positives (Dog):** 11 | **False Positives:** 6
- **True Positives (Cat):** 10 | **False Negatives:** 3

---

## 💡 **Comparison and Analysis:**
- ✅ **Accuracy Improvement:** From **60% to 70%**.
- ✅ **Better F1-Score:** Enhanced consistency across both classes.
- ✅ **Improved Precision & Recall:** Notably better classification for cats.

## 🚀 **Conclusion:**
Using PCA reduced feature dimensionality while preserving key information, enabling faster training and a **10% improvement in accuracy**. The confusion matrix indicates a reduction in misclassifications, highlighting the effectiveness of dimensionality reduction.

This project demonstrates the importance of feature extraction techniques like PCA for optimizing machine learning models. 🎯🚀🐶🐱
