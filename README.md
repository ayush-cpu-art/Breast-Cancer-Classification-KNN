# Breast Cancer Classification using K-Nearest Neighbors (KNN)

## Objective

Develop a K-Nearest Neighbors (KNN) classification model to predict whether a breast tumor is **Malignant (M)** or **Benign (B)** using the Breast Cancer Wisconsin Diagnostic Dataset.

## Dataset

Breast Cancer Wisconsin Diagnostic Dataset

https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data

## Libraries Used

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Methodology

1. Load the dataset.
2. Perform exploratory data analysis.
3. Check for missing values.
4. Remove unnecessary columns.
5. Encode the target variable.
6. Standardize the features.
7. Split the dataset into training and testing sets.
8. Train a KNN classifier with K = 5.
9. Evaluate the model using Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.

## Results

- Accuracy: ~96%
- Precision: ~97%
- Recall: ~93%
- F1-Score: ~95%

The KNN model achieved high classification performance with only a few misclassified samples.

## Conclusion

The KNN classifier performed effectively in classifying breast tumors as benign or malignant. Feature scaling significantly improved the model because KNN relies on distance calculations. While the model achieved high accuracy, one limitation is that KNN can become computationally expensive with large datasets since it stores all training instances and computes distances during prediction.

## Repository Structure

```
Assignment-4/
│── data/
│   └── data.csv
│── images/
│   ├── confusion_matrix.png
│   └── accuracy.png
│── Assignment-4.ipynb
│── README.md
│── requirements.txt
└── .gitignore
```