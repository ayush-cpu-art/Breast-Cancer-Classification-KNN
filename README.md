#  Breast Cancer Classification using K-Nearest Neighbors (KNN)

##  Overview

This project implements a **K-Nearest Neighbors (KNN)** classification model to classify breast tumors as **Malignant (M)** or **Benign (B)** using the Breast Cancer Wisconsin Diagnostic Dataset.

Feature standardization is applied before training because KNN relies on distance calculations between data points.

---

##  Objective

- Explore the breast cancer dataset.
- Perform data preprocessing and exploratory analysis.
- Handle unnecessary columns.
- Encode the target variable.
- Standardize numerical features.
- Train a KNN classifier.
- Evaluate the classification performance using multiple metrics.

---

##  Dataset

**Dataset:** Breast Cancer Wisconsin Diagnostic Dataset

The dataset contains **569 samples** and **30 numerical features** used for classification.

### Target Classes

- **M** → Malignant
- **B** → Benign

---

##  Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

##  Methodology

1. Load the dataset.
2. Perform exploratory data analysis.
3. Check for missing values.
4. Remove unnecessary columns.
5. Encode the target variable.
6. Split the dataset into training and testing sets using an 80:20 split.
7. Standardize the features using `StandardScaler`.
8. Train a KNN classifier with **K = 5**.
9. Evaluate the model using Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.
10. Visualize the model performance.

---

##  KNN Configuration

| Parameter | Value |
|---|---|
| Algorithm | K-Nearest Neighbors |
| Number of Neighbors (K) | 5 |
| Feature Scaling | StandardScaler |
| Train/Test Split | 80/20 |

---

##  Results

The KNN model achieved the following performance on the test dataset:

| Metric | Score |
|---|---:|
| Accuracy | 95.61% |
| Precision | 97.44% |
| Recall | 90.48% |
| F1-Score | 93.83% |

### Confusion Matrix

```text
                 Predicted
              B          M
Actual B     71          1
Actual M      4         38
