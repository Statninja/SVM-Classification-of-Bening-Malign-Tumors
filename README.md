# **SVM Tumor Classification**

## **Project Overview**
This project leverages **Support Vector Machines (SVM)** to classify breast tumors into benign and malignant categories. Using the **Wisconsin Breast Cancer Dataset**,  tumor features are analyzed to train a robust model for accurate medical diagnosis.

---

## **Objectives**
- Classify tumors as **benign** or **malignant**.
- Visualize data using key plots like **pairplot**, **3D visualizations**, and the **Correlation Heatmap**.
- Assess the performance of **SVM** for accurate classification for cancerous tumors.

---

## **Key Visualizations**

### 1. **Pairplot**: 
Displays relationships between multiple tumor features.
![Pairplot](https://raw.githubusercontent.com/Statninja/SVM-Classification-of-Bening-Malign-Tumors/refs/heads/main/output_11_0.png)

### 2. **3D Visualization**:
Explores the decision boundary of SVM in three dimensions.
![3D Plot]([path/to/3d_plot.png](https://github.com/Statninja/SVM-Classification-of-Bening-Malign-Tumors/blob/main/SVM%203D.png))

### 3. **Correlation Heatmap**:
Shows feature correlations in the dataset, highlighting important relationships.
![Confusion Matrix]([path/to/confusion_matrix](https://github.com/Statninja/SVM-Classification-of-Bening-Malign-Tumors/blob/main/output_13_0.png)

---

## **Methodology**
1. **Data Preprocessing**:
   - Cleaned and normalized the dataset.
   - Handled missing values and standardized features.

2. **Model Selection**:
   - Employed **SVM** with a linear and radial basis function (RBF) kernel for classification.

3. **Evaluation**:
   - Used **cross-validation** and performance metrics such as **accuracy**, **precision**, and **recall**.

---
### Classification Report - Conclusions
![Classification Report &Confusion matrix](https://raw.githubusercontent.com/Statninja/SVM-Classification-of-Bening-Malign-Tumors/refs/heads/main/Classification%20Report.png)

The SVM classification model achieved **96% accuracy** in predicting whether tumors are benign or malignant. The precision and recall metrics indicate excellent performance, especially in identifying malignant tumors with **97% recall**. However, there were **5 misclassifications** in benign predictions. Parameter tuning could further optimize the model.

### Recommendations:
- Fine-tune hyperparameters and test ensemble methods to reduce misclassifications.

### Next Steps:
- Assess the **generalizability** (model's ability to perform well on unseen data) on larger, more diverse datasets to improve model robustness.


---
## **How to Run the Project**
1. Clone the repository.
   ```bash
   git clone https://github.com/your-repo/SVM-Tumor-Classification.git
