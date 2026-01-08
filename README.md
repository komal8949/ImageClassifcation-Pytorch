# 🖼️ Image Classification using PyTorch

A **deep learning image classification model** built using **PyTorch** to classify images into **5 different classes**:  
**Janish, Komal, Riya, Gracy, and Harsh**.

The model is trained on a dataset of approximately **500 images** and achieves **~92% classification accuracy**.

---

## 📌 Project Overview

This project demonstrates an **end-to-end deep learning pipeline**:
- Dataset preparation
- Image preprocessing & augmentation
- CNN model training using PyTorch
- Model evaluation and accuracy analysis

The goal is to accurately classify images into one of the five predefined classes.

---

## 🧠 Classes

The model predicts one of the following classes:

- Janish  
- Komal  
- Riya  
- Gracy  
- Harsh  

---

## 📊 Dataset Details

- Total images: **~500**
- Number of classes: **5**
- Images per class: ~100
- Image format: JPG / PNG
- Dataset split:
  - **Training:** 80%
  - **Validation:** 10%
  - **Testing:** 10%

> ⚠️ Dataset is private / custom-created and used for educational purposes.

---

## 🏗️ Model Architecture

- Convolutional Neural Network (CNN)
- Key layers:
  - Convolution + ReLU
  - Max Pooling
  - Fully Connected Layers
  - Softmax Output

Built entirely using **PyTorch**.

---

## ⚙️ Technologies Used

- **Python**
- **PyTorch**
- **Torchvision**
- **NumPy**
- **Matplotlib**
- **PIL (Python Imaging Library)**

---

## 🔄 Workflow

1. Image data loading & labeling
2. Image preprocessing & normalization
3. Data augmentation
4. CNN model design
5. Model training
6. Evaluation & accuracy calculation
7. Prediction on unseen images

---

## 📈 Model Performance

- **Training Accuracy:** ~92%
- **Validation Accuracy:** ~90%
- **Loss Function:** Cross Entropy Loss
- **Optimizer:** Adam

The model performs well with minimal overfitting.

---

## 📸 Sample Predictions

*(Add sample prediction images here)*

```text
Input Image → Predicted Class: Komal
Confidence Score: 0.94
