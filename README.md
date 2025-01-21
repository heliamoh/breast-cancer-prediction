## **Introduction**
Breast cancer is one of the most common cancers worldwide and a leading cause of cancer-related deaths among women. Early detection and accurate classification of breast tumors as either **benign** or **malignant** are critical to improving patient outcomes. Machine learning techniques offer powerful tools to assist in this process by analyzing complex datasets and providing predictions with high accuracy.

In this project, I utilized the[Breast Cancer Wisconsin Dataset](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)) to develop a machine learning pipeline capable of predicting the malignancy of breast tumors. The project involved the following steps:
- **Data Preprocessing**: Standardizing the features to ensure consistent scaling.
- **Dimensionality Reduction**: Applying **Principal Component Analysis (PCA)** to reduce the dataset's dimensionality while retaining most of its variance.
- **Model Training and Evaluation**: Comparing the performance of seven different machine learning algorithms, including Logistic Regression, k-Nearest Neighbors, Support Vector Machines, and Random Forests, to determine the most effective model for this task.

The primary objective of this project was to explore and compare the effectiveness of various classification algorithms in predicting the malignancy of tumors, ultimately identifying the most accurate and efficient model for this critical healthcare application.

---

## **Conclusion**
In this project, we applied **Principal Component Analysis (PCA)** for dimensionality reduction, reducing the dataset's dimensionality from 30 features to 16 principal components. This preprocessing step retained most of the dataset's variance, ensuring that critical information was preserved while improving the efficiency of the machine learning models.

We then trained and evaluated **7 classification algorithms** using the PCA-transformed dataset to compare their performance based on **accuracy**, **precision**, **recall**, and **F1-score**. The results are summarized below.


## **Key Results**

### **1. Logistic Regression**
- Achieved the highest performance with:
  - **Accuracy**: 99.12%
  - **F1-Score**: 0.991

### **2. k-Nearest Neighbors (k-NN)**
- Obtained an accuracy of **95.61%**, making it one of the weaker performers compared to other models.

### **3. SVM (Linear)**
- Achieved an accuracy of **98.25%**, showing excellent performance on the dataset.

### **4. Kernel SVM**
- Matched the linear SVM with an accuracy of **98.25%**, but exhibited slightly better precision (**98.29%**).

### **5. Naïve Bayes**
- Was the weakest performer, with an accuracy of **92.11%**.

### **6. Decision Tree**
- Achieved an accuracy of **95.61%**, similar to k-NN.

### **7. Random Forest**
- Outperformed Decision Trees with:
  - **Accuracy**: 96.49%
  - **F1-Score**: 0.965
