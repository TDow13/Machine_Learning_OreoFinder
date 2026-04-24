# Machine Learning Project: Finding Oreo

**Team Number:** Group 2

**Team Members:**
- Terrance Huang
- Tyler Dow
- Kelly Jiang
- Emily Huang

---

## Abstract
Finding Oreo is a binary image classification that determines whether
a given cat photo is Oreo (a tuxedo cat) or not. It compares three
models: Logistic Regression, K-Nearest Neighbors, and Convolutional 
Neural Network. All three models are trained on a dataset of pictures 
of Oreo alongside public dataset of other cats from Kaggle. We are
comparing these models hold up against each other on this image
classification task.

---

## Dataset
The Non-Oreo pictures are a dataset from Kaggle 
(https://www.kaggle.com/datasets/crawford/cat-dataset) 
and the Oreo dataset are photos taken by team members.
The split is 80/10/10 train-validation-test stratified.

---

## Models
- Logistic Regression
- K-Nearest Neighbors
- Convolutional Neural Networks

---

## How to Run 
1. Install dependencies/libraries: pip install -r requirements.txt
2. Run all cells in order

---

## Preprocessing
- Resize all images to 128 x 128
- Data Augmentation to CNN
- HOG + PCA (95% var.) to LR & KNN
- Standard Scaler

---

## Results (Accuracy)
LR: 87.25% vs KNN: 95.98% vs CNN: 96.11%
