# CIFAR-10 Image Classification using TensorFlow

A deep learning project that classifies color images from the CIFAR-10 dataset using a feedforward neural network implemented with TensorFlow and Keras.

The project explores neural network architecture design, learning rate scheduling, dropout regularization, and model evaluation using a confusion matrix.

---

## Project Overview

Image classification is one of the most common applications of deep learning.

This project trains a neural network capable of classifying images into one of ten categories using the CIFAR-10 dataset.

The notebook demonstrates the complete machine learning workflow:

- Load the dataset
- Data preprocessing
- Model construction
- Hyperparameter tuning
- Model training
- Performance evaluation
- Predictions
- Confusion matrix visualization

---

## Dataset

The CIFAR-10 dataset contains 60,000 color images divided into ten classes.

Classes include:

- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

Each image is:

- 32 × 32 pixels
- RGB (color)

---

## Features

- TensorFlow/Keras implementation
- Feedforward Neural Network
- SELU activation
- AlphaDropout regularization
- Learning Rate Scheduling
- Model evaluation
- Confusion matrix visualization
- Prediction on unseen images

---

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Repository Structure

```text
CIFAR10-Image-Classification/
│
├── notebooks/
│   └── CIFAR10_Image_Classification.ipynb
│
├── images/
│
├── models/
│
├── README.md
├── LICENSE
└── .gitignore
```

---

## Installation

```bash
git clone https://github.com/yourusername/CIFAR10-Image-Classification.git
cd CIFAR10-Image-Classification
```

Create a virtual environment

```bash
python -m venv venv
```

Activate it

Windows

```bash
venv\Scripts\activate
```

macOS/Linux

```bash
source venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## Running the Project

Open

```text
notebooks/CIFAR10_Image_Classification.ipynb
```

Run all cells from top to bottom.

---

## Skills Demonstrated

- Deep Learning
- TensorFlow
- Keras
- Image Classification
- Learning Rate Scheduling
- Regularization
- Hyperparameter Tuning
- Data Visualization
- Confusion Matrix Analysis

---

## Future Improvements

- Convolutional Neural Networks (CNN)
- Data augmentation
- Transfer learning
- Early stopping
- TensorBoard visualization
- Hyperparameter optimization

---

## Author

Samantha Aranibar
