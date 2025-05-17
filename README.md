# Machine-Learning-Image-Classification-Brain-Cancer-MRI-Dataset
# 🧠 Brain Tumor MRI Classification with CNN

This project presents a convolutional neural network (CNN) to classify MRI images of brain tumors into one of three categories. The model was trained using a custom-labeled dataset containing over 6,000 images and is capable of achieving high classification accuracy.

---

## 📚 Dataset Overview

- Source: [Brain Cancer MRI Dataset on Kaggle](https://www.kaggle.com/datasets/orvile/brain-cancer-mri-dataset)
- Total Images: ~6,056
- Classes:
  - `brain_tumor`
  - `brain_glioma`
  - `brain_menin`
- Image Resolution: All images were resized to **224x224**.
- Split:
  - Training: 72.25%
  - Validation: 12.75%
  - Test: 15%

---

## 🧠 Model Summary

| Component      | Configuration               |
|----------------|-----------------------------|
| Architecture   | Sequential CNN              |
| Convolutional Layers | 4 layers (32 → 64 → 128 → 256 filters) |
| Dense Layers   | 256 units + Softmax output  |
| Dropout        | 0.3                         |
| Activation     | ReLU + Softmax              |
| Optimizer      | Adam (lr = 0.0003)          |
| Loss Function  | Categorical Crossentropy    |

---

## 📈 Results

| Metric              | Score    |
|---------------------|----------|
| Final Training Accuracy   | **98.95%** |
| Final Validation Accuracy | **95.60%** |
| Test Set Accuracy         | **96.70%** |

These results indicate that the model generalizes well and performs consistently on unseen data.

---

## 📊 Training Graphs

Training progress can be seen in the accuracy and loss plots. The model converges steadily with minimal overfitting thanks to controlled dropout, data augmentation, and learning rate tuning.

![Image](https://github.com/user-attachments/assets/a3405797-7f4b-43c4-affb-e624685df1c7)


## 🧪Inference
![Image](https://github.com/user-attachments/assets/59e951e6-c5d3-4c2c-9070-871987baaa5e)
