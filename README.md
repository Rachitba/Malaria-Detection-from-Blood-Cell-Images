# Malaria Detection from Blood Cell Images

## Overview
Malaria is a life-threatening disease caused by parasites transmitted through the bites of infected mosquitoes. Early detection is crucial for effective treatment. This project focuses on building a **deep learning model using Convolutional Neural Networks (CNN)** to automatically detect malaria from microscopic images of red blood cells.

The model classifies blood cell images into two categories:
- **Parasitized** (infected with malaria)
- **Uninfected** (healthy cells)

This system aims to assist medical professionals by providing a fast and reliable automated screening method.

---

## Dataset

The dataset used in this project contains microscopic images of red blood cells labeled as infected or uninfected.

Dataset Source:  
Kaggle

Dataset Classes:
- Parasitized
- Uninfected

Each image represents a microscopic view of a red blood cell sample.

---

## Project Workflow

The project follows a typical deep learning pipeline:

1. **Data Collection**
   - Loading malaria cell image dataset

2. **Data Preprocessing**
   - Image resizing
   - Normalization
   - Train-test split

3. **Data Augmentation**
   - Rotation
   - Flipping
   - Zoom transformations

4. **Model Building**
   - Convolutional Neural Network (CNN)
   - Multiple convolution and pooling layers
   - Fully connected dense layers for classification

5. **Model Training**
   - Training the CNN model on labeled data
   - Optimizing using Adam optimizer

6. **Model Evaluation**
   - Accuracy
   - Loss curves
   - Confusion matrix

7. **Prediction**
   - Classifying new blood cell images as infected or healthy

---

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- OpenCV
- Scikit-Learn

---

## Model Architecture

The Convolutional Neural Network includes:

- Convolutional Layers
- Max Pooling Layers
- Dropout for regularization
- Fully Connected Dense Layers
- Sigmoid activation for binary classification

---

## Results

The CNN model successfully learns features from microscopic cell images and can distinguish infected cells from healthy ones.

Evaluation metrics include:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## Applications

This system can be used for:

- Automated malaria screening
- Medical image analysis
- Assisting healthcare professionals
- AI-based disease detection

---

## Future Improvements

Possible enhancements include:

- Using deeper CNN architectures
- Transfer learning (ResNet, VGG)
- Deploying the model as a web application
- Real-time malaria detection from microscope feeds

---

