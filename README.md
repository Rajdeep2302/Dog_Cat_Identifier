# 🐶🐱 Dog vs Cat Image Classifier using PyTorch

A deep learning project to classify images of **dogs** and **cats** using **PyTorch** and **Transfer Learning**. The model achieves an accuracy of **91.22%** on the test dataset.

---

## 📌 Features

- Built using **MobileNetV2** pretrained on ImageNet
- Supports **image classification** for cats and dogs
- Outputs **"Unknown"** for non-dog/cat images
- Training, validation, and test evaluation pipeline
- Clean and modular code for easy customization

---

## 🧠 Model Architecture

- **Base Model**: MobileNetV2 (`torchvision.models.mobilenet_v2`)
- **Classifier Head**: AdaptiveAvgPool → Flatten → Linear (2 classes)
- **Loss Function**: CrossEntropyLoss
- **Optimizer**: Adam
- **Accuracy**: 91.22% on the test dataset

---

## 📁 Dataset Structure

The project assumes the following folder structure after unzipping `archive.zip`:

