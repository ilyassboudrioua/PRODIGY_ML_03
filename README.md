# PRODIGY_ML_03 – Cats vs Dogs Classification with SVM

Task 3 of my Machine Learning internship at **Prodigy InfoTech**.

## Objective
Classify images of cats and dogs using a **Support Vector Machine (SVM)**.

## Dataset
[Cat and Dog (Kaggle)](https://www.kaggle.com/datasets/tongpython/cat-and-dog) – 3000 images sampled, 80/20 train/test split

## Approach
| Method | Features | Accuracy |
|---|---|---|
| 1 | HOG (edges, 128×128 grayscale) + SVM (RBF) | 73.7 % |
| 2 | MobileNetV2 pre-trained features + SVM (RBF) | **98.0 %** |

Same SVM, different features: deep features from a pre-trained CNN (transfer learning) make the difference.

## Tools
Python, Scikit-learn, Scikit-image, TensorFlow/Keras, Matplotlib
