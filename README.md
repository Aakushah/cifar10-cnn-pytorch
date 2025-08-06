# CIFAR-10 Image Classifier

Image classification on CIFAR-10 using a convolutional neural network (CNN) built and trained with PyTorch in Colab

## 📦 Dataset
CIFAR-10 is a collection of 60,000 32x32 color images in 10 classes, with 6,000 images per class. The 10 classes are:

`airplane`, `automobile`, `bird`, `cat`, `deer`, `dog`, `frog`, `horse`, `ship`, `truck`.

## 🧠 What’s Inside
- Built a CNN model using PyTorch to classify CIFAR-10 images.
- Loaded and preprocessed the data using `torchvision.datasets` and `DataLoader`.
- Used cross-entropy loss and SGD optimizer for training.
- Evaluated model performance on the test dataset using accuracy and visualized some predictions.

## 🚀 How to Run
1. Open the Google Colab notebook: [CIFAR-10_Classifier.ipynb](CIFAR-10_Classifier.ipynb)
2. Run all cells from top to bottom.
3. Make sure to enable GPU (Runtime > Change runtime type > GPU) in Colab for faster training.

## 📊 Results
The model was trained for multiple epochs and achieved strong classification accuracy. Some example predictions are shown at the end of the notebook.

## 📁 Files
- `CIFAR-10_Classifier.ipynb`: Main notebook containing code, explanations, training, and evaluation.

## 📌 Requirements
- Python 3.x
- PyTorch
- torchvision
- Google Colab (recommended)

---
**Author:** Aakash Prasad Sah  
**Date:** August 2025
"""
