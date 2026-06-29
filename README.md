# Human Activity Recognition using Smartphones

## Overview

This project implements Human Activity Recognition (HAR) using the UCI HAR Dataset. It compares the performance of a Gaussian Naive Bayes classifier trained on:

- All available features
- Features reduced using K-Means clustering

The dataset is downloaded automatically from the UCI Machine Learning Repository.

---

## Dataset

Human Activity Recognition Using Smartphones Dataset

- Source: UCI Machine Learning Repository

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- BeautifulSoup
- Requests

---

## Machine Learning Workflow

1. Download dataset automatically
2. Load training data
3. Encode activity labels
4. Standardize features
5. Train Gaussian Naive Bayes on all features
6. Reduce features using K-Means clustering
7. Train Gaussian Naive Bayes on reduced features
8. Compare accuracy and training time

---

## Results

The notebook prints:

- Accuracy using all features
- Accuracy using reduced features
- Training time
- Number of selected features

---

## How to Run

```bash
pip install -r requirements.txt
```

Open the notebook and run all cells.

The dataset is downloaded automatically.
