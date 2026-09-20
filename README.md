# 🩺 Breast Cancer Classification using KNN

A machine learning classification project that uses the K-Nearest Neighbors (KNN) algorithm to classify breast tumors as benign or malignant.

## 📌 Overview

This project implements an end-to-end machine learning workflow for breast cancer classification using the Wisconsin Diagnostic Breast Cancer dataset.

The workflow includes data preprocessing, feature standardization, KNN model training, and evaluation using multiple classification metrics.

## 🎯 Objectives

- Load and explore the breast cancer dataset
- Analyze dataset structure and target distribution
- Handle unnecessary columns
- Encode the target variable
- Split the data using stratified sampling
- Standardize numerical features
- Train a KNN classifier
- Evaluate the model using classification metrics and a confusion matrix

## 📊 Dataset

The dataset contains **569 samples** and 30 numerical features describing characteristics of cell nuclei.

### Target Variable

`diagnosis`

| Value | Meaning |
|---|---|
| `B` | Benign |
| `M` | Malignant |

Class distribution:

- Benign: **357**
- Malignant: **212**

The `id` column and an empty `Unnamed: 32` column were removed before model training.

## ⚙️ Methodology

### 1. Data Preparation

- Loaded the dataset using Pandas
- Inspected dataset shape and data types
- Checked for missing values
- Removed unnecessary columns

### 2. Target Encoding

The diagnosis labels were encoded as:

```text
B → 0
M → 1
