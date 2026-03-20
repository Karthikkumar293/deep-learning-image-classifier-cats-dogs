# deep-learning-image-classifier-cats-dogs
# 🐶🐱 

## 📌 Overview
This project implements a deep learning model to classify images of cats and dogs.
It uses Convolutional Neural Networks (CNNs) to automatically learn features from images and predict whether
the image contains a cat or a dog.

---

## 🚀 Features
- Image classification using CNN
- Data preprocessing and augmentation
- Model training and validation
- Accuracy and loss visualization
- Prediction on custom images

---

## 🧠 Model Architecture
The model is built using a Convolutional Neural Network (CNN) which includes:
- Convolutional layers (feature extraction)
- Activation functions (ReLU)
- Pooling layers (downsampling)
- Fully connected (dense) layers
- Output layer with sigmoid activation (binary classification)

---

## 🛠️ Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
  

---

## 📂 Project Structure


  cat-vs-dog-classification/
│
├── dataset/
│ ├── train/
│ ├── test/
│
├── model/
│ └── model.h5
│
├── deep_learning_2.ipynb



---

## 📊 Dataset

The dataset contains images of cats and dogs divided into:
- Training set
- Testing set

## 📥 Dataset

The dataset used in this project is manually provided and contains labeled images of cats and dogs.

### Dataset Details:
- Total Images: 1000
- Categories:
  - Cats
  - Dogs
- Image Format: JPG/PNG
- Image Size: Resized to (e.g., 150x150)

### Directory Structure:
dataset/
├── train/
│   ├── cats/
│   ├── dogs/
├── test/
│   ├── cats/
│   ├── dogs/



---

## ⚙️ Installation

1. Clone the repository:

git clone https://github.com/Karthikkumar293/cat-vs-dog-classification.git
cd cat-vs-dog-classification
