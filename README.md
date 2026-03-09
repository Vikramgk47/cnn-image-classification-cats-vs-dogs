# CNN Cat vs Dog Image Classifier

This project implements a **Convolutional Neural Network (CNN)** to classify images of cats and dogs.

The dataset is automatically collected using the **Bing Image Downloader**, organized into training, validation, and test sets, and then used to train a CNN model using **TensorFlow/Keras**.

---

## Project Overview

Image classification is a key application of deep learning in computer vision.  
In this project, a CNN model is trained to distinguish between two classes:

- Cats
- Dogs

The model learns visual patterns such as edges, textures, and shapes from images to make predictions.

---

## Dataset Creation

Images were automatically downloaded using the **bing-image-downloader** library.

The dataset was then organized into:

```
train/
validation/
test/
```
 
Each split contains:

```
cats/
dogs/
```

---

## Model Architecture

The CNN model includes:

- Convolutional layers (feature extraction)
- Max pooling layers (downsampling)
- Dense layers (classification)

The final output layer uses **sigmoid activation** for binary classification.

---

## Training Results

- Training Accuracy: ~91%
- Test Accuracy: ~61%

The training graphs show signs of **overfitting**, which is common when training CNNs on smaller datasets.

---

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Bing Image Downloader

---

## What I Learned

- How to automatically create image datasets
- How images are represented as NumPy arrays
- How to prepare datasets for CNN training
- How convolutional neural networks extract visual features
- How to evaluate model performance using accuracy and loss

---

## Author

Vikram Krishnareddy  
MS Data Science — University of Connecticut 
