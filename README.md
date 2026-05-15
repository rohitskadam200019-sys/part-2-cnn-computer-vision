# Part 2: Computer Vision Problem Formulation and CNN Prototype

## Project Overview

This project focuses on building a Convolutional Neural Network (CNN) model for image classification using a synthetic manufacturing defect dataset.

The objective of this project is to understand how CNNs use convolution layers, activation functions, pooling layers, flatten layers, and dense layers to learn visual patterns from image data.

The model classifies product surface images into different defect categories.

---

# Dataset Information

## Dataset Classes

The dataset contains four image classes:

- normal
- scratch
- dent
- stain

Each image belongs to only one category.

---

# Problem Type

This dataset represents an Image Classification problem because the objective is to classify each image into one of the predefined defect categories.

The dataset does not contain bounding boxes or pixel-level annotations, therefore it is not an object detection or segmentation problem.

---

# Tasks Performed

## Task 1: Problem Identification
- Identified the dataset as an image classification problem
- Explained why classification is appropriate

---

## Task 2: Dataset Exploration
- Counted total classes
- Counted images per class
- Displayed sample images
- Checked image dimensions
- Analyzed dataset balance

---

## Task 3: Image Preprocessing
- Resized images to 128x128
- Normalized pixel values
- Split dataset into training and validation sets
- Applied image augmentation

---

## Task 4: CNN Model Creation

A CNN model was created using TensorFlow/Keras with:

- Convolution layers
- ReLU activation
- MaxPooling layers
- Flatten layer
- Dense layer
- Softmax output layer

---

## Task 5: Model Training and Evaluation

The CNN model was trained and evaluated using:

- Training Accuracy
- Validation Accuracy
- Training Loss
- Validation Loss
- Confusion Matrix
- Sample Predictions

---

# Task 6: CNN Concept Explanation

## What is Convolution?

Convolution is a process where filters are applied over images to detect important visual patterns such as edges, textures, scratches, and shapes.

---

## Why is Pooling Used?

Pooling reduces the size of feature maps and helps the model focus on important features while reducing computational complexity and overfitting.

---

## Why is ReLU Commonly Used in CNNs?

ReLU introduces non-linearity into the model and helps CNNs learn complex image patterns efficiently. It also improves training speed.

---

## Why are CNNs Better than Regular Feed-Forward Networks for Image Data?

CNNs are better for image processing because they automatically learn spatial features and patterns from images while using fewer parameters compared to regular neural networks.

---

# Business Use Case Mapping

This type of computer vision solution can be used in the manufacturing industry for automated quality inspection.

CNN-based systems can automatically detect product defects such as scratches, dents, and stains from product images. This helps improve product quality, reduce manual inspection effort, and increase production efficiency.

---

# Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- OpenCV
- Scikit-learn
- Seaborn

# Conclusion

The project successfully demonstrated how CNNs can be used for image classification in manufacturing defect detection. The CNN model learned visual patterns from product surface images and classified defects into multiple categories with good performance.
